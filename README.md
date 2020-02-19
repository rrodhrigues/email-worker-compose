## Email-Worker-Compose

Projeto com intuito de usar o Docker para Deploy de aplicações 

### Requisitos 
docker v19.03.6
docker-compose v1.21.2

### 1 Passo - db

Execute os seguintes comandos

```
docker-compose up -d
```
```
docker-compose exec db psql -U postgres -c '\l'
```
```
docker-compose down'
```

