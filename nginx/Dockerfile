#FROM ubuntu:22.04

#LABEL maintainer="bureevlr"

#RUN apt update && \
#    apt install -y -q curl gnupg2
#RUN curl http://nginx.org/keys/nginx_signing.key | apt-key add -

#RUN apt update && \
#    apt install -y -q nginx

#ADD nginx.conf /etc/nginx/
#ADD server.conf /etc/nginx/conf.d

#EXPOSE 443 80

#CMD ["nginx", "-g", "daemon off;"]
FROM nginx
COPY . /usr/share/nginx/html

