FROM php:7.0-cli
RUN mkdir /usr/src/myapp
COPY index.php /usr/src/myapp
WORKDIR /usr/src/myapp
EXPOSE 3000
CMD [ "php", "-S", "0.0.0.0:3000", "index.php" ]