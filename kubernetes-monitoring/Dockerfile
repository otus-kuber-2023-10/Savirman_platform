FROM centos:centos7
RUN mkdir /app/
RUN yum -y install epel-release && \
    yum -y install nginx && \
    usermod -u 1001 nginx && groupmod -g 1001 nginx
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
