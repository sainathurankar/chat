# Chat Spring Boot App

A chat spring boot application implemented using Web Socket and dockerized. Follow the instructions below to build and run the Docker container.

## Build Docker Image

To build the Docker image, use the following command:

```bash
docker build -t chat-spring-boot:latest .
```

## Run Docker Container

To run the Docker container and expose the Spring Boot application on port 8080, use the following command:

```bash
docker run -p 8080:8080 chat-spring-boot:latest
```

## Note
This command starts a Docker container from the chat-spring-boot:latest image and maps port 8080 from the container to port 8080 on the host machine. The Spring Boot application inside the container will be accessible at http://localhost:8080.

Make sure you have Docker installed and running on your machine before executing these commands.