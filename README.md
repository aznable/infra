# Aznable Infra

An implementation of a reverse proxy network using [NGINX proxy](https://github.com/nginx-proxy/nginx-proxy) and [Acme Companion](https://github.com/nginx-proxy/acme-companion).

## Installation

Install `Aznable Infra` by cloning its Github repository:

```
git clone https://github.com/aznable/infra.git
cd infra
cp .env.example .env
```

## Basic Usage

To run the containers, just execute `docker-compose up -d` in the same directory:

```
$ docker-compose up -d
```