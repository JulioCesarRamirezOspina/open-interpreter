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

# Ejecutar stack chatwoot

```shell
sudo docker stack deploy -c images/chatwoot/docker-compose.yml chatwoot
```

# Ejecutar stack forms

```shell
sudo docker stack deploy -c images/formbricks/docker-compose.yml forms
```

# Ejecutar stack redis

```shell
sudo docker stack deploy -c images/redis/redis.yml redis
```

# Ejecutar stack n8n

```shell
sudo docker stack deploy -c images/n8n/n8n.yml n8n
```