# Shared
The shared library contains common utilities, models, and configurations used across multiple microservices in the system. It promotes code reuse and consistency across services.

## Features
- Common Models: Shared data models used by various services.
- Utility Functions: Reusable utility functions for common tasks.
- Configuration Management: Centralized configuration settings for microservices.
- Error Handling: Standardized error handling mechanisms.
- Logging: Shared logging utilities for consistent logging across services.
- Client Libraries: Pre-built clients for interacting with other microservices.

## Technologies Used
- Java 21
- Spring Boot
- Maven
- GitHub Packages

## Usage
To use the shared library in your microservice, add the following dependency to your `pom.xml
```xml

<repositories>
    <repository>
        <id>github</id>
        <url>https://maven.pkg.github.com/CorsairOps/*</url>
    </repository>
</repositories>

<dependencies>
<dependency>
    <groupId>com.corsairops</groupId>
    <artifactId>shared</artifactId>
    <version>${sharedVersion}</version>
</dependency>
</dependencies>
```