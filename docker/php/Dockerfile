FROM php:7.4-fpm

# composer install
COPY --from=composer:latest /usr/bin/composer /usr/bin/composer

RUN apt-get update && apt-get install -y git zip unzip \
  && docker-php-ext-install pdo_mysql
