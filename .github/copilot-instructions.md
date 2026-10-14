# Soc Ops Workspace Guidelines

## Mandatory Development Checklist

Before finishing a change:

- Run `cd socops && ./mvnw checkstyle:check` for lint and formatting checks.
- Run `cd socops && ./mvnw clean package`.
- Run `cd socops && ./mvnw test`.
- For web changes, run `cd socops && ./mvnw spring-boot:run` and smoke-test `http://localhost:8080`.

## Project Map

- Soc Ops is a Java 21, Spring Boot 3.4.2 social bingo app in `socops/`, using Thymeleaf and static browser assets.
- Under `com.socops`, `web` owns HTTP endpoints, `service` owns board logic, `model` owns records/enums, and `data` owns prompts.

## Conventions

- Keep `BoardAssembler` pure and static; it builds boards, toggles cells, and detects row, column, and diagonal wins.
- Keep `BingoRestController` thin. Preserve immutable-style records and defensive copies.
- Put templates in `socops/src/main/resources/templates/`, assets in `socops/src/main/resources/static/`, and focused JUnit tests in `socops/src/test/java/`.
- Preserve the existing game workflow and responsive UI. Follow the [CSS utilities](.github/instructions/css-utilities.instructions.md) and [frontend design](.github/instructions/frontend-design.instructions.md) guidance.