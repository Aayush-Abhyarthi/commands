Docker commands



docker ps.  -> shows all the running containers
docker ps -a -> shows all the containers
docker images -> shows all the images available locally
docker pull <image name:version> -> pulls the image locally
docker rmi <image name> -> deletes the image locally
docker run -it alpine sh -> runs the image in a container in interactive mode
docker run -d alpine tail -f /dev/null -> runs the image in a container in detached mode
docker exec -it <container-id-or-name> sh -> runs the image in interactive mode after the container was created in detached mode.
docker stop <container-id> -> stops the running container
docker rm <container-id> -> deletes the running container
docker run -p 8080:8080 <image-name>
