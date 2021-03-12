# Django, Postgresql, Nginx + Docker

# Run developmeent
```
docker-compose up --build
```

Down the containers
```
docker-compose down -v
```

# Run Production
```
docker-compose -f docker-compose.production.yml up --build
```

Down the containers
```
docker-compose -f docker-compose.production.yml down -v
```