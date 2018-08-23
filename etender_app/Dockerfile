#use a php image
FROM php:5.6-fpm-alpine

COPY etender-dev /var/www/html/
COPY ./php.ini /usr/local/etc/php/php.ini

RUN docker-php-ext-install mysqli