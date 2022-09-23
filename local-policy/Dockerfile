#-------------docker build--------------#
FROM --platform=arm64 ubuntu:latest

LABEL MAINTAINER "DevOpsBeast"

WORKDIR /app

RUN apt-get udpate

EXPOSE 65536

RUN  apt-get update

CMD ["/usr/sbin/nginx", "-g", "daemon off;"]
