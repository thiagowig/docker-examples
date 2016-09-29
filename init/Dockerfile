
FROM ubuntu

MAINTAINER Thiago Fonseca

RUN apt-get update

RUN apt-get install -y nginx

ADD example /etc/nginx/sites-enabled/default

RUN ln -sf /dev/stdout /var/log/nginx/access.log
RUN ln -sf /dev/stderr /var/log/nginx/error.log

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"] 
