# plant-watering-iot-project
Our goal is to have a combination of hardware and software that take care of multiple home plants using sensors and acuators as well as external data from APIs.


------
# Setup
## 0. Prerequisits
1. [docker](https://docs.docker.com/engine/install/)
1. [docker-comopose](https://docs.docker.com/compose/install/)

## 1. Up and Running
Run the following command to let the container users read/write from and to the volumes.

```bash
echo "USER=$(id -u)\nGROUP=$(id -g)" > .env
```

Run the following code to start all the containers in the architecture:

```bash
docker-compose up
```