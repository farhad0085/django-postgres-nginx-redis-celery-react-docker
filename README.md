# Django, Postgresql, Nginx, Redis, Celery, React + Docker
Dockerize Django with Postgresql, Nginx, Redis, Celery and React (DRF as API)

## Run developmeent
```
docker-compose up --build
```

Down the containers
```
docker-compose down -v
```

## Run Production
```
docker-compose -f docker-compose.production.yml up --build
```

Down the containers
```
docker-compose -f docker-compose.production.yml down -v
```