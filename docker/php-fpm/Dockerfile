FROM phpdockerio/php71-fpm:latest

RUN apt-get update \
    && apt-get -y --no-install-recommends install  php-memcached php7.1-mysql php-redis php7.1-gd php-xdebug \
    && apt-get clean; rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/* /usr/share/doc/*


WORKDIR "/application"