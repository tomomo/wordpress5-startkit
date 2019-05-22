# wordpress5-startkit

Easily build a wordpress development environment using docker-compose.

```sh
cp .env.example .env
docker volume create --name=wordpress-db
docker-compose up -d --build
```
