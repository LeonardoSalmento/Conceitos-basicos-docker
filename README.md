# Conceitos-basicos-docker
Repositório para descrever os conceitos básicos do docker


## Comandos e conceitos
 - ```docker run``` baixar/rodar uma imagem do docker e rodar o container
 Ex: docker run hello-world

 - ```docker build``` criar uma imagem a partir de um dockerfile
 Ex: docker build -t <DOCKER_USERNAME>/getting-started-todo-app .

 - ```docker image ls``` listar imagens que estão no pc


 - ```docker push``` subir a imagem para sua conta na dockerhub ou outro registry
 Ex: docker push <DOCKER_USERNAME>/getting-started-todo-app
