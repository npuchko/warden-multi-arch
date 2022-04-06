ARG PHP_VERSION
FROM ghcr.io/drpayyne/warden-php-m2:${PHP_VERSION}-deb
USER www-data
RUN echo 'alias m="php bin/magento"' >> ~/.bashrc
