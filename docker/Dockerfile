FROM php:8-apache-buster

RUN apt-get update && apt-get upgrade -y

WORKDIR /var/www/html

COPY . /var/www/html
RUN ln -sf pmwiki.php index.php
RUN umask 002 \
    && mkdir /var/www/html/wiki.d /var/www/html/pub/htmlcache /var/www/html/uploads \
    && chmod 777 /var/www/html/wiki.d /var/www/html/pub/htmlcache /var/www/html/uploads

COPY docker/000-default.conf /etc/apache2/sites-available/
RUN ln -sf /etc/apache2/mods-available/rewrite.load /etc/apache2/mods-enabled/
