#Docker: Ferramenta essencial para Desenvolvedores

# Install Docker Ubunut
https://docs.docker.com/install/linux/docker-ce/ubuntu/#install-using-the-repository

# Test docker
docker container run hello-world

#imagem debian
docker container run debian bash --version

#mostra todos os container independete do status
docker container ps -a

#mostrar todos os container independente do status
docker container ls -a

#remove o container no fim do processo
docker container run --rm debian bash --version

#entrar no terminal do container
docker container run -it debian bash

#criando um container com nome
docker container run --name mydebian -it debian bash

#reutilizar um container
docker container start -ai {NAME_CONTAINER}

#mapeando portas do container
docker container run -p 8080:80 nginx

