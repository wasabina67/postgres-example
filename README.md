# postgres-example
Postgres example

```bash
docker run -d --rm \
--name postgres-example \
-e POSTGRES_USER=user \
-e POSTGRES_PASSWORD=password \
-p 5432:5432 \
postgres:latest
```

```bash
docker ps -a
```

```bash
docker exec -it postgres-example bash
```

```bash
psql --version
```

```bash
psql -U user
```

```bash
docker stop  postgres-example
```
