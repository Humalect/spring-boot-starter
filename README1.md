# spring-boot-starter

Hello World sample shows how to deploy [SpringBoot](http://projects.spring.io/spring-boot/) RESTful web service application with [Docker](https://www.docker.com/) and with [Kubernetes](https://kubernetes.io/)

#### Prerequisite 

Installed:   
[Docker](https://www.docker.com/)   
[git](https://www.digitalocean.com/community/tutorials/how-to-contribute-to-open-source-getting-started-with-git)   

Optional:   
[Docker-Compose](https://docs.docker.com/compose/install/)   
[Java 1.8 or 11.1](https://www.oracle.com/technetwork/java/javase/overview/index.html)   
[Maven 3.x](https://maven.apache.org/install.html)


#### Steps

1. Clone source code from git
2. Build Docker image
3. Run Docker Container


### Run with docker-compose 

Build and start the container by running 

```
docker-compose up -d 
```

#### Test application with ***curl*** command

```
curl localhost:8080
```

response should be:
```
Hello World
```

##### Stop Docker Container:
```
docker-compose down
```
