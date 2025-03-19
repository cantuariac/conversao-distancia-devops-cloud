# conversao-distancia

## Desafio 1 - Docker

Exercício prático feito durante Imersão DevOps && Cloud.

[Link do desafio](https://imersao.devopspro.com.br/desafio/desafio-devops-e-cloud/desafio-1-docker/)

## Comandos

Build docker image
 ```
docker build -t conversao-distancia .
 ```

Run docker container
 ```
docker container run -d -p 5000:5000 conversao-distancia
 ```

Push Docker Hub repository
 ```
docker push <namespace>/<repository>:<tag>
 ```