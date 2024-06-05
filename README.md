
# API GATEWAY ST1 - Fiap

Serviço criado utilizando Spring Cloud.\

Utiliza o Spring cloud api gateway.

Requisitos para rodar:\
Java 22\
Docker(opcional, caso queira montar a imagem e executar)\
https://docs.docker.com/desktop/install/windows-install/ \
https://docs.docker.com/desktop/install/linux-install/

Possibilidade de utilização do Docker para rodar\
Versão da openjdk para rodar: 22-jdk-slim

Como gerar imagem Docker para poder rodar:\
docker build -t api-gateway:0.0.1 .

Possui docker-compose para executar após gerar imagem:\
api-gateway\docker-compose.yml

Para subir a image, basta rodar (você precisa ter o docker instalado):\
docker-compose up -d