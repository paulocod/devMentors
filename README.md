comando para criar o container do redis
```bash
  docker run --name redis-cache -p 6379:6379 -d redis
```
comando para buildar image
```bash
 DOCKER_BUILDKIT=1 docker build --tag node-devmentors -f docker/prod/Dockerfile . --no-cache
```
