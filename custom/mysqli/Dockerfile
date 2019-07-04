FROM php:7.3.3-apache

# Install mysqli extension
RUN docker-php-ext-install mysqli gettext && docker-php-ext-enable mysqli

# use production php.ini settings
RUN cp /usr/local/etc/php/php.ini-production /usr/local/etc/php/php.ini

# Set locales
RUN apt-get clean && apt-get update && apt-get install -y locales && \
locale-gen nl_NL.UTF-8 UTF-8


