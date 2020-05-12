# Docker-wordpress-wpjson
This docker-compose get image of wordpress build with centos, nginx, php-fpm, and mysql 8.0.

if for some reason your mysql is not running, in your terminal

#docker run -it *yourcontainername* "/bin/bash"

once on container console type

#mysqld -D

## Wordpress plugin used

1. Woocommerce
2. JSON API
3. JSON API Auth
4. JSON API User
5. JWT Authentication for WP-API

## Wordpress credentials (run with init db)

/wp-admin
username: admin
password: secret123
email: info@yoursite.com

