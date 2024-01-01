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

## Postman

Postman folder is provided in this repository.

1. Import Into Workspace: Book, User Auth and Workspace will import all global variables, api endpoints,
parameters and authentication tokens used for testing.
2. Create a User: Register enpoint will create a new user
3. Login: Login endpoint will provide access and refresh token save them into global variables (!important)
4. Update: Update user fields will update user information in database
5. Verify and Refresh Token: Provided for proper frontend implementation
6. Delete User: Authenticated user is deleted using this endpoint
7. Book: Create, Get All, Delete, Update, Fetch one is provided explicitly with proper authentication or readonly options



