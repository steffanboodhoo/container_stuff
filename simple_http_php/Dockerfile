#use php - apache image
FROM php:5.6-cli

# Make port 9000 available to the world outside this container
#EXPOSE 9000

#copy code to html
COPY cm-test-repo /var/www/html/
WORKDIR /var/www/html
#
#mount the folder to the host

CMD ["php","-S","0.0.0.0:9000"]
