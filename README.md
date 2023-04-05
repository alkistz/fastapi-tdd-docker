# Documentation

## To build all the images

```bash
docker-compose up -d --build
```

## To access the db

```bash
docker-compose exec web-db psql -U postgres
```
