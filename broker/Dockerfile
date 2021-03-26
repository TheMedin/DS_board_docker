FROM python:3.8.5-alpine

ENV PYTHONUNBUFFERED=1

ADD broker.py /broker/

WORKDIR /broker/

RUN pip3 install requests