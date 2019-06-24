# Docker-Nuxt-Template

This is a template for easy development of Nuxt.js on Docker

## Dependency

Docker v18.2.0
docker-compose v1.23.2
Nuxt.js v2.0.0

## Setup(for mac)

```bash
$brew install docker
$brew cask install docker

$open /Applications/Docker.app
```

Register account according to the message

```bash
$git clone https://github.com/Umisyo/Docker-Nuxt-Template

$cd Docker-Nuxt-Template

$docker-compose build nuxt
```

## Usage

```bash
$docker-compose run create-nuxt-app
```

Make the following changes to package.json to allow access from the host OS.

```diff
- "dev": "nuxt"
+ "dev": "HOST=0.0.0.0 PORT=3000 nuxt"
```

Then type the following command.

```bash
$docker-compose run nuxt yarn install
```

To start the server, just type the following command.

```bash
$docker-compose up
```

## License

This software is released under the MIT License, see [LICENSE](https://github.com/Umisyo/Docker-Nuxt-Template/blob/master/LICENCE).

## Authors

Souta Kusunoki a.k.a Umisyo or そーとく