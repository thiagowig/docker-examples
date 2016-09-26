FROM ubuntu

MAINTAINER Thiago Fonseca

RUN apt-get update

RUN apt-get install -y nginx

ADD example /etc/nginx/sites-enabled/default

EXPOSE 8080