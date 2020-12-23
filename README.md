# spring-boot-docker-hello-world
Spring boot + docker 


Clone source code from git
$  git clone https://github.com/ebruogdur/spring-boot-docker-hello-world.git .

Build project with Maven
$ mvn clean install

Build Docker image
$ docker build -t="spring-boot-docker" .

Run Docker image
$ docker run -p 8080:8080 -it --rm spring-boot-docker
