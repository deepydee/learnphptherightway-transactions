FROM php:8.1-fpm

COPY docker/php/php.ini /usr/local/etc/php/php.ini
COPY . /srv/app

RUN usermod -u 1000 www-data
USER www-data

# RUN chown -R www-data:www-data /srv/app

WORKDIR /srv/app