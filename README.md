# docker-php7.4-apache

A Debian LAMP container

It's on [docker-hub](https://hub.docker.com/repository/docker/niclab/php7.4/) and [github](https://github.com/Akito-K/docker-php7.4)

## tags and links
* `latest` [(main/Dockerfile)](https://github.com/Akito-K/docker-php7.4/blob/main/Dockerfile)

## how to build

```sh
git clone git@github.com:Akito-K/docker-php7.4.git
cd docker-php7.4
docker build --rm -t niclab/php7.4 .
```

## running

```sh
docker-compose up -d
```