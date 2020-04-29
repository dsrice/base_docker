FROM python:3.7
ENV PYTHONUNBUFFERED 1
RUN mkdir /code
RUN apt-get update
WORKDIR /code
ADD requirement.txt /code/
RUN pip install -r requirement.txt
ADD . /code/
WORKDIR /base-api

EXPOSE 8000