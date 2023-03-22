Primer docker creat des de un Dockerfile
==========================================

## Crear la imatge
````
$ docker build -t tonifp/02:v0 .
o també:

chmod +x build.sh

$ ./build.sh

````

## Per executar aquesta imatge feu: 
````
$ docker run --name test -it --rm tonifp/02:v0

o també:

chmod +x run.sh

$ ./run.sh

````

