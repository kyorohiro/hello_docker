# Hello Docker


```
docker swarm init
docker stack deploy -c docker-compose.yml getstartedlab
docker service ls
docker service ps getstartedlab_web
docker container ls -q
docker stack rm getstartedlab
docker swarm leave --force
```
