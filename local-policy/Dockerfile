--------image build----------
FROM ubuntu:dtrq

LABEL MAINTAINER "DevOpsBeast"

WORKDIR /app

RUN apt-get udpate

EXPOSE 900

RUN  apt-get update

CMD ["/usr/sbin/nginx", "-g", "daemon off;"]
