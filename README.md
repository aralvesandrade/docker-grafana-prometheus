Iniciar containers usando comando `docker-compose`

```
docker-compose up
#ou
docker-compose up -d
```

Carregar configuracoes do prometheus

```
docker exec -it {container_prometheus} kill -HUP 1
```
