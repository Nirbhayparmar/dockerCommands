# dockerCommands

## all docker commands-

- docker pull <name of image> = to download the images from dockerhub
- docker run <name of image> = to run the image to make containers
- docker start <name/id of container> = to start the container from the id or container name
- docker stop <name/id of container> = to stop the container from the id or container name
- docker ps = to get the ids of docker containers
- docker rm <the-container-id or name>
- docker push YOUR-USER-NAME/imageName = to push the image on dockerhub
- docker build -t <name of image> = to build the image from the dockerfile
- docker exec -it <name/id of container> <"bash">
- docker kill <name/id of container> = to direclty kill the container

  
## flags-

- (-d) - run the container in detached mode (in the background)
- (-p) - 80:80 (host port:container port) map port 80 of the host to port 80 in the container
- (-v) - /C/Users/Nirbhay/tensorflow://notebooks (/your local directory):(/container directory) to map the local directory to container directory
- (--name) - to set the name of container
- (-it) - to make the container interactive terminal
- (-t) - to set the name of tag for the image
- (-all) - to get ids or info about all the containers
  
- [docker documantation](https://docs.docker.com/engine/reference/run/)
