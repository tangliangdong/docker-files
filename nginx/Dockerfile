# Version: 0.0.1
FROM nginx:1.16.1
MAINTAINER tangliangdong Turnbull "xiaotang188@gmail.com"
RUN apt-get update 
# RUN apt-get install net-tools
# RUN apt-get install vim-gtk

COPY nginx.conf /etc/nginx/

VOLUME /mnt/nginx-resource

EXPOSE 80

# docker build -t mynginx:v1 .

# docker run -d -v /mnt/nginx-resource:/mnt/nginx-resource -p 8888:80 --name nginx mynginx:v1