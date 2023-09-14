# crear red 

```shell
sudo docker network create -d overlay yosoft-network
```

# Ejecutar stack traefik

```shell
docker stack deploy -c traefik.yml traefik
```

# Remover stack traefik

```shell
sudo docker stack rm traefik
```

# Ejecutar stack penpot

```shell
sudo docker stack deploy -c images/penpot/docker-compose.yml penpot
```