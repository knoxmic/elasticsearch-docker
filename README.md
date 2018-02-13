elasticsearch
=============

## Build

```sh
docker build -t elasticsearch .
```

```sh
docker tag elasticsearch index.docker.io/knoxmic/elasticsearch:2.4.6
docker push knoxmic/elasticsearch:2.4.6
```

## Startup

```sh
docker-compose up -d
```
