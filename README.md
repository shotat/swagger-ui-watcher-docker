# swagger-ui-watcher-docker

Docker image for [swagger-ui-watcher](https://github.com/moon0326/swagger-ui-watcher)

```sh
$ docker run -it --init --rm -p 8000:8000 -v "$(pwd)/swagger:/swagger" shotat/swagger-ui-watcher
```
