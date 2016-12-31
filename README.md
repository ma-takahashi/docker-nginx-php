# docker-nginx-php

## nginx

```
docker build -t docker-nginx-php/nginx -f nginx/Dockerfile ./nginx
docker tag docker-nginx-php/nginx 864031815705.dkr.ecr.ap-northeast-1.amazonaws.com/docker-nginx-php/nginx
docker push 864031815705.dkr.ecr.ap-northeast-1.amazonaws.com/docker-nginx-php/nginx
```

## phpfpm

```
docker build -t docker-nginx-php/php -f phpfpm/Dockerfile ./
docker tag docker-nginx-php/php 864031815705.dkr.ecr.ap-northeast-1.amazonaws.com/docker-nginx-php/php
docker push 864031815705.dkr.ecr.ap-northeast-1.amazonaws.com/docker-nginx-php/php
```
