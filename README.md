# Postgres Docker Image

Postgres mit deutscher Locale. Sonst "baugleich" mit "postgres" von Docker Hub.

## Wie benutze ich das Image?

In diesem Repository liegt eine funktionierende `docker-compose.yml` dabei.

## Das Image bauen

Man kann das Image auch selber bauen, wenn man möchte:

```bash
docker build --no-cache --network=host --force-rm -t FROM ghcr.io/schipplock/postgres-docker-image:v16.1.0 .
```
