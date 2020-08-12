# Redis Sentinel
![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/tienyu/redis-sentinel)

## How To Use
```bash=
docker run --name redis-sentinel --net=host -e REDIS_PORT=<port> -p <port>:<port> -v <volume path>:/data tienyu/redis-sentinel
```
