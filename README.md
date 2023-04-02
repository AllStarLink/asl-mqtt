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
make ; Make is not working yet. Copy the files to /var/docker/asl-matt for now.
cd /var/docker/asl-mqtt
```
## Configure

Edit the `environment:` section of docker-compose.yml

Docker Compose is sensitive to indentation. Be sure to keep things lined up. 

## Running
Start the normal docker-composer ways. In the directory where docker-compose.yml exists do 
- `docker-dompose up -d`

Subscribe to all topics
- `mosquitto_sub -t "#" -v`

## Credits
This work is based on other work from:
- https://github.com/sgofferj/ami2mqtt
- https://github.com/mscdex/node-asterisk
