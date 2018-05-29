# Install Docker Ubunut
https://docs.docker.com/install/linux/docker-ce/ubuntu/#install-using-the-repository

# Test docker
docker container run hello-world

#imagem debian
docker container run debian bash --version

#mostra todos os container independete do status
docker container ps -a

#remove o container no fim do processo
docker container run --rm debian bash --version

#entrar no terminal do container
docker container run -it debian bash