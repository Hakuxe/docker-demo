# Docker basic commands

## Gerenciando docker images

``` bash
# Listar as imagens docker locais contidas no computador
docker image

# Remover uma docker image local
docker rmi [nome-da-imagem] 
```

## Gerenciando docker containers

``` bash
# Listar os containers inicializados
docker ps

# Listar todos os container disponíveis localmente 
docker ps -a

# criando um docker container 

# Inicializando docker container
docker start [nome-do-container]

# Parando um docker container 
docker stop [nome-do-container]
```
