# Use the official PHP image with Apache
FROM php:8.0-apache

# Install PHP extensions needed for MySQL
RUN docker-php-ext-install mysqli

# Copy the app code into the container
COPY ./index.php /var/www/html

# Expose port 80 (the default port for Apache)
EXPOSE 80
