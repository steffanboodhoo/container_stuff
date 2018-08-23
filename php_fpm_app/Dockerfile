#use php - apache image
FROM php:5.6-fpm-alpine

# Make port 80 available to the world outside this container
#EXPOSE 9000

#copy code to html
COPY cm-test-repo /var/www/html/

RUN docker-php-ext-install mysqli