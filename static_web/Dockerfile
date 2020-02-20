# Version: 0.0.1
FROM ubuntu:14.04
MAINTAINER tangliangdong Turnbull "xiaotang188@gmail.com"
RUN apt-get update  && apt-get install -y nginx
RUN apt-get install vim-gtk
RUN echo 'Hi, I am in your container' >/usr/share/nginx/html/index.html
#RUN echo "daemon off;" >>/etc/nginx/nginx.conf
EXPOSE 80

