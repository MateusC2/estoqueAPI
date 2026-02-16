# Comando p iniciar docker

```
docker-compose up -d --build
docker-compose up --build
```

up: Sobe os serviços (banco e app).
-d: Detached (libera seu terminal para você continuar usando).
--build: Força o Docker a recriar a imagem da sua API (importante caso você tenha mudado o código ou o package.json recentemente).

# Verificar se deu certo

```
docker-compose ps
```

# Ver logs

```
docker-compose logs -f app
```

# Apagar e remover tudo

```
docker-compose down
