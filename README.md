# laravel-docker

laravel-docker is a template empty project that help you setup new Laravel projects using local Docker environment.

How to use it
-------------

### Clone the repository

```shell
git clone https://github.com/guidoarce89/laravel-docker.git
```

### Install composer dependencies

```shell
docker run --rm -v $(pwd):/app composer install
```

### Run the docker containers

```shell
docker-compose up -d
```

The first time, docker-compose will build your application.

If you need, for some reason, rebuild your application, you could run this command

```shell
docker-compose up -d --build
```
