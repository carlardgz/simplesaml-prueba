FROM php:8.1-apache
COPY ./simplesaml /var/www/simplesaml
COPY ./simplesaml/000-default.conf /etc/apache2/sites-available/000-default.conf
RUN service apache2 restart
EXPOSE 80
