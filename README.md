# nginx-php
Minimalists nginx + php

[code]
docker run --restart=always \
--name nginx \
-p 80:80 \
-h nginx \
-d patrickz/php-nginx:latest
[code]
