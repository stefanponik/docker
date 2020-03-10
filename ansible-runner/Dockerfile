FROM python:3.7.6

LABEL maintainer="stefanponik@gmail.com"

RUN apt update -y && \
    apt install sshpass -y && \
    pip install ansible==2.9.6

RUN mkdir -p /ansible

WORKDIR /ansible