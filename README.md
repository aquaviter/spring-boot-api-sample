# Spring boot API Sample (Docker)

## Build

Build docker container and push the image to repository.

```
$ ./gradlew build buildDocker
```

## Run

Run docker image.

```
$ docker run -p 8080:8080 -t aquaviter/spring-boot-api-sample
```

## Request

```
$ curl http://localhost:8080/hello-world?name=hogehoge
{"id":1,"content":"Hello, hogehoge!"}
```
