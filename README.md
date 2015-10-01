[![forthebadge](http://forthebadge.com/images/badges/built-with-love.svg)](http://forthebadge.com)
[![forthebadge](http://forthebadge.com/images/badges/uses-js.svg)](http://forthebadge.com)

Available on:
- development: http://docker:8080/
- production: http://docker:80/

Commands:
- to stop & remove all containers: $ docker rm -f $(docker ps -a -q)
- docker-compose build --no-cache
- to build & run project: $ docker-compose up -d
- $ docker-compose run nodejs bash

npm install -g bower
bower install angular --allow-root --save
sanitize
localization