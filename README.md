docker_lamp
=====================
docker-compose definition for deployment of generic lamp server with Traefik, support for max 5 sites 


Docker-compose
--------------

This puppet script configures a complete docker-compose setup for a lamp server. Which
consists of:

 - mysql
 - php-apache
 - traefik 2.x

It is started using Foreman which creates:

 - .env file

The puppet script generates:

running docker-compose project

Result
------
Working webserver with mysql for generic lamp sites. 

Limitations
-----------
This has been tested.
