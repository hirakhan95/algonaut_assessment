# Algonaut Assessment

## Build and Start project with django

### 1. Require Migrations 
```bash
python manage.py makemigrations
python manage.py migrate
```
It will create sqlite database and create required tables

### 2. Run Server
```bash
python manage.py runserver
```

## Build and Start server on docker

- PreRequisite: [Docker](https://docs.docker.com/engine/install/) 
- Tested on: Docker version 23.0.5, build bc4487a

### Build

```bash
docker compose build
```

### Start docker container

```bash
docker compose up
```

or in background

```bash
docker compose up -d
```

### Shutdown docker containers

```bash
docker compose down
```
