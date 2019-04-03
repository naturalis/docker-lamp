docker_lamp
=====================
docker-compose definition for deployment of generic lamp server with Traefik 


Docker-compose
--------------

This puppet script configures a complete docker-compose setup for a lamp server. Which
consists of:

 - mysql
 - php-apache
 - traefik

It is started using Foreman which creates:

 - .env file
 - traefik.toml

The puppet script generates:

running docker-compose project

Result
------
Working webserver with mysql for generic lamp sites. 

Limitations
-----------
This has been tested.
