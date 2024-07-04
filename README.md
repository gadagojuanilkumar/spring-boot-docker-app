  
# Simple Spring Boot with Docker Application#

Start the Docker by using the following command

```bash
$ sudo service docker start
```

Install Git using the following command

```bash
$ sudo yum install git
```
Install Maven using the following command

```bash
$ sudo yum install maven
```

Git clone the Repo using the following command

```bash
$ git clone https://github.com/gadagojuanilkumar/spring-boot-docker-app.git
```

Enter the directory by using the following command

```bash
$ cd spring-boot-rest-api
```

Clean the maven packages using below command

```bash
$ mvn clean package
```

Build the docker image using the following command

```bash
$ docker build -t spring-boot-rest-api .
```

Run the Docker container using below command

```bash
$ docker run -d -p 8080:8080 spring-boot-rest-api
```

The application will be accessible at http://localhost:8080/

