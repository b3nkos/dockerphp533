FROM centos:centos6.7
MAINTAINER "Cristian Martínez" <cristianandres92@gmail.com>
RUN yum -y install httpd
RUN service httpd start
RUN yum install -y php php-mysql
RUN chkconfig httpd on
RUN service httpd restart
RUN yum -y install vim
RUN yum -y install curl
RUN yum -y install wget

EXPOSE 80
