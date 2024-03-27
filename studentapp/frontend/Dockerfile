FROM centos:7

RUN yum install httpd -yum

COPY index.html /var/html/index.html

EXPOSE 80

CMD httpd -DFOREGROUND