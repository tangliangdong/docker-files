# Version: 0.0.1
FROM tomcat:8
MAINTAINER tangliangdong Turnbull "xiaotang188@gmail.com"
RUN apt-get update 
RUN apt-get install net-tools
COPY server.xml /usr/local/tomcat/conf

VOLUME /mnt/nginx-resource
VOLUME /usr/local/tomcat/webapps

EXPOSE 8080

# docker build -t supervisor:v1 .

# docker run -d -p 9001:8080 -v /mnt/nginx-resource:/mnt/nginx-resource -v /mnt/service/webapps:/usr/local/tomcat/webapps --name supervisor --link mysql:mysql supervisor:v1

# 关联nginx文件服务器的数据卷
# docker run -d -p 9001:8080 -v --volumes-from nginx -v /mnt/service/webapps:/usr/local/tomcat/webapps --name supervisor --link mysql:mysql supervisor:v1