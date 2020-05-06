# Cluster elastic com docker swarm
### 1 - Criando os certificados
```
docker-compose -f create-certs.yml run --rm create_certs
```
### 2 - Deploiando a stack
```
docker stack deploy -c docker-compose.yml elk
```