# Magento Local worker image


PHP [![](https://images.microbadger.com/badges/image/mygento/php:5.6-fpm.svg)](https://microbadger.com/images/mygento/php:5.6-fpm)

NGINX [![](https://images.microbadger.com/badges/image/mygento/nginx:backports.svg)](https://microbadger.com/images/mygento/nginx:backports)

MYSQL
[![](https://images.microbadger.com/badges/image/mygento/mysql:5.6.svg)](https://microbadger.com/images/mygento/mysql:5.6)


REDIS
[![](https://images.microbadger.com/badges/image/redis:3.svg)](https://microbadger.com/images/redis:3)


DB HOST: db

DB Name: magento

DB user/pass: mygento

docker exec -ti -u www-data m1-php /var/www/public/

docker exec -ti m1-php /bin/bash

stop/remove all Docker containers: docker rm $(docker ps -a -q)
