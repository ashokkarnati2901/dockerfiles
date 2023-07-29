### Dockerfiles

Dockerfile is a declarative way of creating our own images. Dockerfile references will provide us some useful commands to create the images.


Files name should be Dockerfile.

### How to build the docker image

docker build -t [docker-hub-url]/[your-username]/[image-name]:version .

### How to push your image to Docker Hub

docker push [your-username]/[image-name]:version