## Docker-tutorial

### Como apagar todos os containers

#### Parar todos os contêineres em execução

```bash
docker stop $(docker ps -aq)
```

#### Remover todos os contêineres

```bash
docker rm $(docker ps -aq)
```

#### Remover todas as imagens

```bash
docker rmi $(docker images -q)
```

#### Remover todos os volumes

```bash
docker volume prune
```
