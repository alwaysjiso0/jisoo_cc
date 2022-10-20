# Dockerize Codeigniter App With docker-compose

Dockerfile and docker-compose.yml files are referenced from https://github.com/firmanJS/Dockerize-Codeigniter-With-docker-compose

## Test Running Application

```sh
## runing with docker compose
docker-compose -f docker-compose.yml up --build
# or run in background process
docker-compose -f docker-compose.yml up --build -d
```

```sh
app running in port 8181 ---> cek in browser
```

```sh
phpmyadmin running in port 8282 ---> cek in browser
```

```sh
login with username `ci` and password `ci`
```
