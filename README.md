# fastAPI_python

Make sure you have [Docker Engine](https://docs.docker.com/engine/install/) installed first

```shell
docker run --name fastAPI_python -p 5434:5432 -e POSTGRES_PASSWORD=password -d postgres
```

```shell
fastapi dev main.py
```