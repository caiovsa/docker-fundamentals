FROM redhat/ubi8

LABEL maintainer="Animals4life"

RUN yum -y install httpd

COPY index.html /var/www/html/

COPY containerandcat1.jpg /var/www/html/

ENTRYPOINT ["/usr/sbin/httpd", "-D", "FOREGROUND"]

EXPOSE 80

