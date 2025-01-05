FROM php:8.2-fpm

# Instala dependências
RUN apt-get update && apt-get install -y \
    curl \
    zip \
    unzip \
    git \
    libpq-dev \
    libzip-dev \
    && docker-php-ext-install pdo pdo_mysql zip

# Instala o Composer
COPY --from=composer:2 /usr/bin/composer /usr/bin/composer

# Copy custom NGINX configuration
COPY docker/nginx/default.conf /etc/nginx/default.conf

# Copy custom PHP configurations
COPY docker/php/custom.ini /usr/local/etc/php/conf.d/custom.ini

# Define o diretório de trabalho
WORKDIR /var/www
