# DOCKER PHP & MYSQL & NGINX

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](#)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](#)

# New Features!

  - Isolated Nginx (webserver) with Basic configuration for nginx server
  - Isolated PHP server that support fastcgi (fpm)
  - isolated mysql service
  - Handle the services in docker-compose file


### Installation
###### `Here i use Ubuntu 18.4 As my operating system`
First install docker and docker compose in your machine
Validate if this already installed in your machine or not by this commands
```sh
$ sudo docker --version
$ sudo docker-compose --version
```

in the path of docker compose file 
```sh
$ sudo docker-compose build --no-cache
$ sudo docker-compose up
```

License
----
MIT
