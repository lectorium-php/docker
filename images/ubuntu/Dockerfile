FROM ubuntu:latest

RUN apt update && apt install -y nginx

ENTRYPOINT ["/usr/sbin/nginx", "-g", "daemon off;"]
#ENTRYPOINT ["tail", "-f", "/dev/null"]

EXPOSE 80