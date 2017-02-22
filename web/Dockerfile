FROM smebberson/alpine-apache:2.0.0

RUN ln -sf /dev/stdout /var/log/apache2/access.log && \
    ln -sf /dev/stderr /var/log/apache2/error.log

#COPY env/httpd.conf /etc/apache2/httpd.conf

RUN mkdir -p /run/apache2/

EXPOSE 80

WORKDIR /var/www/localhost/htdocs

COPY web /var/www/localhost/htdocs