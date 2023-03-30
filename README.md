# AllStarLink MQTT

Expermental mqtt clients. Nothing much works, yet. Not even these instructions.

## Requirements
- Install assumes Linux but should run anywhere with docker support.  
- docker, docker-compose and make. 
- https://github.com/AllStarLink/asl-mqtt-mosquitto or MQTT broker of choice.
  
## Install
`apt install docker docker-compose make`

Clone this repo to directory of choice, usually `/usr/src`.
```
cd asl-mqtt
make
cd /var/docker/asl-mqtt
```
## Configure

## This work is based on
- https://github.com/sgofferj/ami2mqtt
