# kafka-stack-docker

Kafka full stack (Kafka, Zookeeper, Kafka Magr) installation and execution using docker-compose

## Container management

Use shell script `docker_containers [run|start|stop|status]`. Details of each action is as under:

### `run`

- pull all docker images (if not found locally).
- install the stack components in their own docker containers.
- start containers using own docker network so each container can talk to the other one.

### `start`

Start all non-running Kafka containers.

### `stop`

Stop all running Kafka containers.

### `status`

Check status of Kafka containers.
