# crowdfunding-crud-app

A simplified crowdfunding platform split into five Spring Boot microservices.

> Coursework · Software Engineering · 2025-2 · finished

## Goal
Practice microservice architecture: each service (campaigns, comments, payments,
rewards, users) owns one responsibility and its own data, talks to the others over
REST, and is built, tested and deployed on its own.

## Stack
- Java 21, Spring Boot 3.5, Gradle (Kotlin DSL)
- JSON files for storage
- Docker / Docker Compose
- JUnit 5, GitHub Actions (CI)
- Render (cloud deploy)

## How to run
```bash
docker compose up --build
```
Services: campaigns `:8080`, comments `:8081`, payments `:8082`, rewards `:8083`, users `:8084`.

## What I took from it
- How to structure an application as containers and run it with Docker.
- How to write unit and integration tests that actually guarantee the behavior.
- How a Spring Boot web application is organized.
- How CI/CD works, from automated tests to automated deploys.
