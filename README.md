# SimpleHome-Container

Docker Container containing SimpleHome Server WIP

## Build and run container

```shell
docker-compose build
docker-compose up -d
```

## Go into container

```shell
docker-compose exec -u application app /bin/bash
```

# Docker Dev

## Build and run container
```shell
docker-compose -f docker-compose_dev.yml build
docker-compose -f docker-compose_dev.yml up
```

# Run cypress test
```shell
docker-compose exec -u application app /bin/bash
npx cypress run
```