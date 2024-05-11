FROM php:latest

RUN pecl install xdebug && \
    docker-php-ext-enable xdebug

COPY php.ini /usr/local/etc/php/