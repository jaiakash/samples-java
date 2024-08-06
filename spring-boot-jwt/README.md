# Keploy Sample Java - JWT Token Verification and Spring Boot

This repository contains a sample project that demonstrates the integration of Keploy with JWT (JSON Web Token) authentication in a Spring Boot application.

## Prerequisites

Before getting started, make sure you have the following installed:

- Latest version of JDK
- Install [Keploy](https://keploy.io/docs/server/installation/)
- Postman for testing APIs

## Getting Started

To get started, clone the repository:

```bash
git clone https://github.com/jaiakash/samples-java.git
cd spring-boot-jwt
```

## Native Usage

## Docker Usage

To run the application with Docker, follow these steps:

1. Build the Docker image:

   ```bash
   docker build -t spring-boot-jwt .
   ```

2. Run the Docker container:

   ```bash
   docker run -p 8080:8080 spring-boot-jwt
   ```

The application will be accessible at `http://localhost:8080`.
