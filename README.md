elasticsearch
=============

## Build

```sh
docker build -t elasticsearch .
```

```sh
docker tag elasticsearch index.docker.io/knoxmic/elasticsearch:5.6.7
docker push knoxmic/elasticsearch:5.6.7
```

## Startup

```sh
docker-compose up -d
```
