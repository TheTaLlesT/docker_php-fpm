FROM php:7.0.33-fpm-alpine
RUN apk add autoconf make g++ curl-dev libxml2-dev
RUN pecl install solr
RUN apk del autoconf make g++ curl-dev libxml2-dev
RUN docker-php-ext-enable solr
