# Kong Compose

A simple docker-compose set up to get kong up and running for testing

## Install

```shell
docker build -t kong:custom docker/kong
docker-compose run --rm kong kong migrations bootstrap
```