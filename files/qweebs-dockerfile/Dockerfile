FROM wordpress:latest

COPY ./uploads.ini /usr/local/etc/php/conf.d

RUN apt-get update && \
    apt-get install -y libxml2-dev

RUN docker-php-ext-install soap && docker-php-ext-enable soap
