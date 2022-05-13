# learning-docker-and-kubernetes

In this lecture our image will be the Nginx web server

Docker's default image "registry" is called Docker Hub (hub.docker.com)

Start a new container using: docker container run --publish 80:80 nginx

Open http://localhost in your browser
Downloaded image 'nginx' from Docker Hub

Started a new container from that image

Opened port 80 on the host IP

Routes that traffic to the container IP, port 80

docker container run --publish 80:80 --detach nginx

docker container ls

docker container stop 690

docker container ls

docker container ls -a

docker container run --publish 80:80 --detach --name webhost nginx

docker container ls -a

docker container logs webhost

docker container top

docker container top webhost

docker container --help

docker container ls -a

docker container rm 63f 690 ode

docker container ls

docker container rm -f 63f

docker container ls -a
