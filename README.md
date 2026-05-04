# Java Application Automation with Gradle

## Project Overview
This project demonstrates build automation and dependency management for a Java application using Gradle. It integrates a CI/CD pipeline to streamline the development lifecycle.

## Tech Stack
- **Build Tool:** Gradle 8.7
- **Language:** Java 21
- **Testing:** JUnit Jupiter (JUnit 5)
- **CI/CD:** Jenkins Pipeline

## Automation Steps
1. **Dependency Management:** All libraries are managed in `app/build.gradle`.
2. **Build Automation:** Controlled via `./gradlew build`.
3. **CI/CD:** Automated via `Jenkinsfile` for continuous integration.

## Verification
To run the build locally:
./gradlew build
