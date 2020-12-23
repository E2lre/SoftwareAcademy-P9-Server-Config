# SoftwareAcademy-P9-Zuul-Server

## Installation
todo

###Docker image construction in project directory :

docker build --build-arg JAR_FILE=target/*.jar -t p9-config .

### Docker execution :

docker run -p 9101:9101 --name Config p9-config


### Test zuul-serveur 
* http://localhost:9101/microservice-zuul-server/default
* http://localhost:9101/microservice-patients/default




