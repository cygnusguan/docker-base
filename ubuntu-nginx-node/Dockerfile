FROM ubuntu:16.04
MAINTAINER Steven

RUN echo 'deb http://ubuntu.csie.ntu.edu.tw/ubuntu/ dapper main restricted universe multiverse' >> /etc/apt/sources.list && \
    apt-get update && \
    apt-get install -y vim nginx nodejs npm&&\
rm -rf /var/lib/apt/lists/*
