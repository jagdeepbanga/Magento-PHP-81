# Magento PHP 8.1 Docker Image

### Inspiration
Inspired from Laravel Sail
https://github.com/laravel/sail

## Docker Container
```
jagdeepbanga/magento-php81
```

## Use Container
```
docker run jagdeepbanga/magento-php81
docker exec -it {containerName} /bin/sh
php -v
PHP 8.1
```

## Build & Push to DockerHub
```
docker build -t jagdeepbanga/magento-php81 .
docker login && docker push jagdeepbanga/magento-php81
```
