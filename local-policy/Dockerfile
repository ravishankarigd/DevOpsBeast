FROM ubuntu:latest

LABEL MAINTAINER "DevOpsBeast"

WORKDIR /app

RUN apt-get udpate

EXPOSE 800

RUN  apt-get update

CMD ["/usr/sbin/nginx", "-g", "daemon off;"]
