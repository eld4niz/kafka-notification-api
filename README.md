# Real-time notification API built with Golang

This project demonstrates a real-time notification system implemented in Golang, utilizing Apache Kafka for message processing. The Kafka server is set up using Docker containers for easy deployment.

## Prerequisites

Before running this project, make sure you have the following installed:

- Go (Golang): [Installation Guide](https://golang.org/doc/install)
- Docker: [Installation Guide](https://docs.docker.com/get-docker/)
- Apache Kafka: [Installation Guide](https://kafka.apache.org/downloads)


## 2. Starting Kafka Server

1. Open a terminal and navigate to the project directory.

2. Start the Kafka server using the provided Docker Compose configuration:

```bash
docker-compose up -d
```

OR

Start your local Kafka server


## 3. Running the Golang Application

- Run cmd/consumer/consumer.go - Starts Consumer Server
- Run cmd/producer/producer.go - Starts Producer Server

## 4. Project Structure

- cmd/
  - consumer/
    - consumer.go
  - producer/
    - producer.go
- pkg/
  - models/
    - models.go 
- docker-compose.yml
- README.md
