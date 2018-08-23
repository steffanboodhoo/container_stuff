#Get an httpd apache image
FROM httpd:2.4-alpine

#COPY ./fpm-httpd.conf /usr/local/apache2/conf/fpm-httpd.conf
#COPY ./fpm-httpd.conf /usr/local/apache2/conf/fpm-httpd.conf
#COPY demo.apache.conf /usr/local/apache2/conf/demo.apache.conf
RUN echo "Include /usr/local/apache2/conf/fpm-httpd.conf" >> /usr/local/apache2/conf/httpd.conf