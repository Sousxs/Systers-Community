# Systers Community

Group project for the Object-Oriented Programming course, built during my ADS program at PUC Goiás (2024). The team was [@jhonzito66](https://github.com/jhonzito66), [@PhilipePedrosa](https://github.com/PhilipePedrosa) and me. This repository is a fork of [jhonzito66/POO](https://github.com/jhonzito66/POO).

Systers is a web app where women join discussion groups, write posts and comment. Groups have member roles and moderation, and members can request mentoring and report content.

## My part

- CRUD for posts and comments
- All front-end pages in Thymeleaf
- Part of the Spring Security setup, together with the team

## Stack

Java 17, Spring Boot 3.3, Spring Security, Spring Data JPA, Thymeleaf, H2, Maven

## Run locally

Requires JDK 17.

```bash
git clone https://github.com/Sousxs/Systers-Community.git
cd Systers-Community
./mvnw spring-boot:run
```

Open http://localhost:8080. The app uses an in-memory H2 database, so data resets when it stops. The H2 console is at http://localhost:8080/h2-console.

## License

MIT, inherited from [jhonzito66/POO](https://github.com/jhonzito66/POO). See [LICENSE](LICENSE).
