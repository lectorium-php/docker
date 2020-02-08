FROM ubuntu:latest

RUN apt update && apt install -y nginx

COPY project /var/www/html

ENTRYPOINT ["/usr/sbin/nginx", "-g", "daemon off;"]

EXPOSE 80