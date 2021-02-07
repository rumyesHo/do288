FROM registry.access.redhat.com/ubi7/ubi:7.7
RUN yum install -y httpd && yum clean all
RUN echo "Helllo from Docker " > /var/www/html/index.html
EXPOSE 80
CMD ["httpd", "-D", "FOREGROUND"]
