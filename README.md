# Magento PHP 8.1 Docker Image

### Magento PHP requirement
Created PHP 8.1 docker image by following magento system requirements.
https://devdocs.magento.com/guides/v2.4/install-gde/system-requirements.html

### Inspiration
Inspired from Laravel Sail
https://github.com/laravel/sail

## Docker Container
```
jagdeepbanga/magento-php-81
```

## Use Container
```
docker run jagdeepbanga/magento-php-81
docker exec -it {containerName} /bin/sh
php -v
PHP 8.1
```

## Build & Push to DockerHub
```
docker build -t jagdeepbanga/magento-php-81 .
docker login && docker push jagdeepbanga/magento-php-81
```
