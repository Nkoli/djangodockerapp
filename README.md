## Basic django app containerized and deployed with Docker, using an nginx docker container as the reverse proxy

### Steps

* Build image
```sh
docker build . -t vda
```

* Run service with
```sh
docker-compose up -d
```