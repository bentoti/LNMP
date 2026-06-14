FROM php:8.5-fpm
RUN docker-php-ext-install mysqli pdo pdo_mysql
RUN echo "date.timezone = America/Fortaleza" > /usr/local/etc/php/conf.d/timezone.ini
