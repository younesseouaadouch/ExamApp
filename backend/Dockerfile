FROM php:8.2-apache

RUN docker-php-ext-install pdo pdo_mysql mysqli

COPY ../*.php /var/www/html/