### Basic commands Docker

**List containers/images/...**
`docker [container]/[image]/[volume] ps`
`docker container ls`
`docker cointainer list`
`-a` is used to get all cointainers/images or volumes, active or not. 

**Start a container**
`docker start [container-name]`

**Running docker**
`docker run`

**Stop docker**
`docker stop`

**Get logs**
`docker cointainer logs [name-container]`

**Inspect cointainer**
`docker container inspect [name-container]`

**Access docker image**
`docker exec -it [container-id] bash`

**Build a image from dockerfile**
`docker build -t ` 

**Run multi docker images**
`docker compose up -d`
Compose is a tool for defining and running multi-container Docker applications. With Compose, you use a YAML file to configure your application’s services. Then, with a single command, you create and start all the services from your configuration
