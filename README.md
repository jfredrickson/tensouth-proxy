# tensouth.net reverse proxy

A deployment of Traefik. This is modeled on the [Traefik Quickstart example](https://docs.traefik.io/#the-trfik-quickstart-using-docker).

## Setup

```
cd traefik
touch acme.json && chmod 600 acme.json
docker-compose up -d
```
