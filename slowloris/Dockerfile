FROM php:7.2-cli

COPY . /usr/src/
WORKDIR /usr/src/

RUN apt-get update
RUN apt-get upgrade -y
RUN apt-get install iputils-ping -y

RUN docker-php-ext-install pcntl