# tensouth.net reverse proxy

A deployment of Traefik. This is modeled on the [Traefik Quickstart example](https://docs.traefik.io/#the-trfik-quickstart-using-docker).

## Setup

```
cd traefik
touch acme.json && chmod 600 acme.json
docker-compose up -d
```

## Dashboard

The Traefik dashboard is only available to localhost on the server. In order to access it, one method is to SSH to the server with a tunnel:

```
ssh -L 8081:localhost:8081 traefik.server.name
```
