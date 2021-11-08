FROM composer:latest

# ADD User and rights
RUN addgroup -g 1000 site \
    && adduser -G site -g site -s /bin/sh -D site \
    && chown -R site:site /var/www/html

# Run in work space
WORKDIR /var/www/html