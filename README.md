# Docker-Nuxt-Template

This is a template for easy development of Nuxt.js on Docker

## Dependency

Docker v18.2.0
docker-compose v1.23.2
Nuxt.js v2.0.0

## Setup(for mac)

```
$ brew install docker
$ brew cask install docker

$ open /Applications/Docker.app
```

Register account according to the message

```
$ git clone https://github.com/Umisyo/Docker-Nuxt-Template

$ cd Docker-Nuxt-Template

$ docker-compose build nuxt
```

## Usage

```
$ docker-compose run create-nuxt-app
```

After that, please develop like normal NuxtJS.

To start the server, just type the following command.

```
$ docker-compose up
```

## License

This software is released under the MIT License, see [LICENSE](https://github.com/Umisyo/Docker-Nuxt-Template/blob/master/LICENCE).

## Authors

Souta Kusunoki a.k.a Umisyo or そーとく