# Spring boot API Sample (Docker)

## Build

Build docker container and push the image to repository.

```
$ ./gradlew build buildDocker
```

Run docker image.

```
$ docker run -p 8080:8080 -t aquaviter/gs-spring-boot-docker
```
