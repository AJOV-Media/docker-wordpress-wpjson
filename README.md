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

## Woocommerece API keys:

**Consumer Key**: ck_e69ffab389c5ab9957b0f3e67a0398047f9d62d9

**Consumer Secret**: cs_30d030a4f3d6a1e132a9b0bdb8fc35f0b81171c7

## HOST

database right now is using woocommerce.local:8095 http port you can edit your hosts...

1. windows - "Drive:\Windows\System32\hosts"
2. mac - "/etc/hosts"

ipaddress_of_your_container woocommerce.local

ex: 192.168.99.100       woocommerce.local