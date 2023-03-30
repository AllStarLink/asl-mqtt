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

Edit the `environment:` section of docker-compose.yml

Docker Compose is sensitive to indentation. Be sure to keep things lined up. 

## Credits
This work is based on other work from:
- https://github.com/sgofferj/ami2mqtt
- https://github.com/mscdex/node-asterisk
