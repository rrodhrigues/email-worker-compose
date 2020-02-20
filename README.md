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

### 2 Passo - db 

Comandos da aula

Subir container
```
docker-compose up -d
```

Checa banco 
```
docker-compose exec db postgres -f /scripts/check.sql
```

Verifica os estados dos container pelo compose
```
docker-compose ps
```

Verifica os logs dos container pelo compose
```
docker-compose logs -f -t
```

