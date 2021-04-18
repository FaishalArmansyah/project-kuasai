FROM php:7.2-apache
RUN apt-get update
RUN docker-php-ext-install pdo pdo_mysql

WORKDIR /var/www/html/
COPY file-web/. .

EXPOSE 80
HEALTHCHECK CMD curl --fail http://localhost:80 || exit 0
