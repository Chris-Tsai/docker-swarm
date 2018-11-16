# Redis on docker swarm

 - docker swarm init
``` 
$ docker swarm init
```

 - docker network init
```
$ docker network create -d overlay --scope swarm chrissoft
```

 - docker service redis init
```
$ docker stack deploy -c redis.yml redis
```
