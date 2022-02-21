# gui-in-docker

on client

install https://sourceforge.net/projects/vcxsrv/

add 
ForwardX11 yes
to ~/.ssh/config


on server

git clone https://github.com/kitamura-tetsuo/gui-in-docker

docker-compose -f ./gui-in-docker/docker-compose.yml up -d