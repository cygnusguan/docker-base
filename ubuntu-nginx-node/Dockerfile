FROM ubuntu:16.04
MAINTAINER Steven

RUN rm /etc/apt/sources.list 
COPY sources.list /etc/apt/sources.list 
RUN echo 'deb http://mirrors.aliyun.com/ubuntu/ trusty main multiverse restricted universe' >> /etc/apt/sources.list && \
    apt-get update && \
    apt-get install -y vim nginx nodejs npm&&\
    ln -s /usr/bin/nodejs /usr/bin/node &&\
    rm -rf /var/lib/apt/lists/*

EXPOSE 80 8080
