# Docker-Compose is magic!
Client-server app to learn basic abilities of docker compose

## Useful commands
* Build new images for compose project `docker-compose build`. This command you should use in the directory with **docker-compose.yml** file.
* `docker-compose up` can build (if images have not already build) and run containers from this images. Also it is running in the directory with **docker-compose.yml** file.
* This command stop and remove all containers which was created with command `docker-compose up`
```
$ docker-compose down
```
* Very cool command
```
docker-compose exec [service name] [command]
```
that help to perform command in running container
