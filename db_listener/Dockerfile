FROM python:3.6-slim

ENV PYTHONPATH /app

WORKDIR /app

COPY . /app

RUN pip install --trusted-host pypi.python.org -r requirements.txt
