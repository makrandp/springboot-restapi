# spring-boot dockerized rest api

* No need download dependencies/build spring-boot app on local machine.
* No need install maven or java on local machine.
* Dockerfile installs Java, Maven and builds the **app.jar** 

# Setup
```$xslt
docker-compose up
```

# Service Usage
```$xslt
http://localhost:8080/greeting
http://localhost:8080/greeting?name=joey
```

# Useful Commands
```$xslt
docker-compose up --force-recreate
docker-compose stop
docker-compose rm
docker-compose down --rmi all
```