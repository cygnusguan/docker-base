FROM ubuntu:16.04
MAINTAINER Steven

RUN echo 'deb http://cn.archive.ubuntu.com/ubuntu/ xenial  main restricted universe multiverse' >> /etc/apt/sources.list && \
    apt-get update && \
    apt-get install -y vim nginx nodejs npm&&\
rm -rf /var/lib/apt/lists/*

EXPOSE 80 8080
