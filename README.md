# Softinsa Training – Spring Boot Final Project (Scaffold)

The Spring Boot starter for the final project of a training programme at Softinsa. It has the project setup (Maven wrapper, web and Thymeleaf dependencies, application entry point and test class) but **no application features yet**.

> **Training project – scaffold only.** Kept as a record of my learning path.

## Tech Stack

- Java 18
- Spring Boot 2.7 (Spring Web, Thymeleaf, DevTools)
- Maven (wrapper included)
- JUnit 5 (Spring Boot Test)

## Getting Started

**Requirements:** JDK 18 or newer

```bash
git clone https://github.com/MooniePT/projetofinal-softinsa.git
cd projetofinal-softinsa/projeto-softinsa/projeto-softinsa
./mvnw spring-boot:run        # Windows: mvnw.cmd spring-boot:run
./mvnw test
```

The app starts on `http://localhost:8080`. No routes are defined yet.

## Project Structure

```
projeto-softinsa/projeto-softinsa/
├── pom.xml
├── mvnw, mvnw.cmd, .mvn/                          # Maven wrapper
└── src/
    ├── main/java/com/projetosoftinsa/projetosoftinsa/
    │   └── ProjetoSoftinsaApplication.java        # Entry point
    ├── main/resources/application.properties
    └── test/java/.../ProjetoSoftinsaApplicationTests.java
```

## What I Learned

- Generating and configuring a Spring Boot project with Spring Initializr and Maven
- How a Spring Boot application starts and how its dependencies are managed
