CI/CD Pipeline using git url, jenkins, maven (build automation tool), docker, hub.docker.com (remoted repository for the images), and EKS ( Elastic Kubernetes Services Cluster). 

# Build Project Using Maven

Maven is java based build tool to generate executable 

packages(jar, ear,war) for java based projects.

```bash
mvn clean package
```

## Create Docker Image which is a read-only file
Docker is a continerization tool.Using docker we can deploy our applications as 

containers using docker images. Containers contains application code and also the softwares,

config files whatever is required for our application to run.

Create docker image using Dockerfile


```docker
docker build -t dockerhandson/spring-boot-mongo .
```

## Deploy Application Using Docker Compose 

```docker-compose 
docker-compose up -d 
```

## List Docker Containers using the Terminal
```docker
docker ps -a
```

## License
[Mithun Technologies](http://mithuntechnologies.co.in)
