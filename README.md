# docker_notes
Notes for common Docker images/containers.


## RabbitMQ

Docker images [here](https://hub.docker.com/_/rabbitmq)

```bash
docker run -d --hostname rmq --name rabbit-server -p 8080:15672 -p 5672:5672 rabbitmq:3-management
```
