FROM ubuntu:20.04

ADD client.py /client/

WORKDIR /client/

RUN apt-get update --fix-missing && apt-get install -y python-pygame
RUN useradd -m -U -s /bin/bash pygame
