# service-discovery

Membros:
 - [Jonathan Cabral](mailto:dev.jonathancabral@gmail.com)
 - [André Graciano](mailto:dev.jonathancabral@gmail.com)

## Build sem Docker
 
    gradlew clean build

## build com docker

    docker build -t sgm/auth -f .\Dockerfile .

    docker run -it -p 8761:8761 sgm/auth
