FROM centos:8

#enabling hosting and downloading git
RUN yum -y install httpd;  yum install git; yum install xinetd; yum clean all; systemctl enable httpd.service;

EXPOSE 80
CMD ["usr/sbin/init"]

