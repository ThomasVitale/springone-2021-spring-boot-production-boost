# SpringOne 2021 - Spring Boot: Production Boost

Slides: https://speakerdeck.com/thomasvitale/spring-boot-production-boost

## Usage

First, package the Book Service application as a container images leveraging the Cloud Native Buildpacks integration
provided by Spring Boot.

```bash
./gradlew bootBuildImage
```

Then, from the project root folder, run Docker Compose for starting both Book Service and PostgreSQL.

```bash
docker-compose up -d
```

The Book Service application is exposed on port 8080.
