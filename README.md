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

Database on this repository will require : https://woocommerce.local:8091/ as path 

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

## SSL

Can be access at https://woocommerce.local:8091/ 

![Valid SSL](https://github.com/AJOV-Media/docker-wordpress-wpjson/blob/master/screenshots/ssl_local.jpg)

In windows just run **certmgr.msc** and under **Current User\Trusted Root Certification Authorities** in <u>Certificates > All Tasks > Import..</u>.  browse for woo.crt.

**Important!**: this works only with  woocommerce.local domain