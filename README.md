**Auto install docker, docker-compose and portainer on centos 7** 

yum install -y wget

wget -O - https://raw.githubusercontent.com/kietcaodev/docker_centos7/refs/heads/main/docker.sh | sh

**If failed** 
docker ps

docker restart <CONTAINER ID>



docker run --name debian --network=host -it debian:latest
