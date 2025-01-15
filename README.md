### Developed by : 
 - **AKOUDAD Imane**
 - **Tounarti Ouiam**
# Microservices Project

This repository contains a set of microservices for managing various functionalities. The project is composed of several services including:

- **Config Server**: Configures and manages microservices using a central configuration server.
- **Eureka Server**: A service discovery server that helps other microservices find each other.
- **Zuul Server**: A gateway server that routes requests to different microservices.
- **Microservice Commandes**: A microservice that manages orders (commandes).
- **Microservice Produits**: A microservice for managing products.

## Services Ports

Each service runs on a different port:

- **Config Server**: 9101
- **Microservice Commandes**: 8888
- **Microservice Produits**: 8082
- **Eureka Server**: 8761
- **Zuul Server**: 9001

## Prerequisites

Before running the services, make sure you have the following:

- Java 17
- Maven

