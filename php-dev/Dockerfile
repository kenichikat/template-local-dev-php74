FROM php:7.4-apache

RUN apt-get update \
 && apt install -y git vim unzip

COPY --from=composer:latest /usr/bin/composer /usr/bin/composer
