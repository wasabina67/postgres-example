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
