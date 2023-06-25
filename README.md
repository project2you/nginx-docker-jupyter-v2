# nginx-docker-jupyter-v2

https://hands-on.cloud/nginx-jupyter-proxy-example/

docker swarm init --advertise-addr 192.168.1.33

docker-compose up -d

#

docker exec -it jupyterhub /bin/bash

adduser 

pip install notebook


#
docker-compose build

docker-compose up


#
docker run -it --rm \
  --name swarmpit-installer \
  --volume /var/run/docker.sock:/var/run/docker.sock \
swarmpit/install:1.9

