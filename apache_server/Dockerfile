#Get an httpd apache image
FROM httpd:2.4-alpine

#COPY ./fpm-httpd.conf /usr/local/apache2/conf/fpm-httpd.conf
COPY ./etender-httpd.conf /usr/local/apache2/conf/etender-httpd.conf
RUN echo "Include /usr/local/apache2/conf/etender-httpd.conf" >> /usr/local/apache2/conf/httpd.conf