FROM php:8.2-cli

WORKDIR /var/www/html

COPY . .

CMD [ "php", "-S","0.0.0.0:8000", "-t", "public" ]

# php -S localhost:8000 -t public