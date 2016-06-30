# Ejemplo Balanceador Ngnix con nodos Node.js y escritura en Redis



Origin Source
For a detailed explanation of the workflow used in this repository, refer to [this post from my blog](http://anandmanisankar.com/posts/docker-container-nginx-node-redis-example/):
[http://anandmanisankar.com/posts/docker-container-nginx-node-redis-example/](http://anandmanisankar.com/posts/docker-container-nginx-node-redis-example/)

For a detailed overview of Containers and Docker, refer to [this post from my blog](http://anandmanisankar.com/posts/container-docker-PaaS-microservices/):
[http://anandmanisankar.com/posts/container-docker-PaaS-microservices/](http://anandmanisankar.com/posts/container-docker-PaaS-microservices/)


### Instrucciones
Deben install docker y docker-compose
Nota. docker solo puede ser instalado en arquitecturas de 64 bits

Luego de instalar, solo deben ingresar estos comandos en la ruta del repositorio

- para compilar
```console
$ docker-compose build
```
- para levantar los servicios
```console
$ docker-compose up
```

- para finalizar los servicios
```console
$ docker-compose kill
```
- para eliminar los containers
```console
$ docker-compose rm
```
- para observar los logs si ejecutan como demonio con -d luego de up
```console
$ docker-compose logs
```
