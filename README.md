## Docker-tutorial

### Como ver a memória ocupada pelo docker

```bash
docker system df
```

### Como parar todos os containers

```bash
docker stop $(docker ps -q)
```

### Como apagar todas as builds de cache

```bash
docker builder prune --all --force
```

### Como apagar todos os volumes

```bash
docker volume ls -q | xargs docker volume rm
```

### Como apagar todos os containers

```bash
docker rm $(docker ps -aq)
```

### Como apagar todas as imagens

```bash
docker rmi $(docker images -q)
```
