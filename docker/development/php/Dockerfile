ARG PHP_VERSION=8.2

FROM php:${PHP_VERSION}-fpm-alpine

RUN apk add --no-cache $PHPIZE_DEPS

RUN docker-php-ext-install session
