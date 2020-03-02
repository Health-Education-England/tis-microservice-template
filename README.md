# TIS Microservice Template

## About
This is a template to be used for TIS microservices with the following
technology:

 - Java 11
 - Spring Boot
 - Gradle
 - JUnit 5

Boilerplate code is to be generated with:
 - Lombok
 - MapStruct

Code quality checking and enforcement is done with the following tools:
 - EditorConfig
 - Checkstyle
 - JaCoCo
 - SonarQube

Error and exception logging is done using Sentry.

## Usage
To use this template, create a new repository from it and follow the TODOs in
the code, with the following additional changes.
 - Update copyright year in [LICENSE](LICENSE).
 - Update copyright year in [TemplateApplication].
 - Update copyright year in [TemplateApplicationTest].
 - Update this README.
 - Provide `SENTRY_DSN` and `SENTRY_ENVIRONMENT` as environmental variables
   during deployment.

## Versioning
This project uses [Semantic Versioning](semver.org).

## License
This project is license under [The MIT License (MIT)](LICENSE).

[TemplateApplication]: src/main/java/uk/nhs/hee/tis/template/TemplateApplication.java
[TemplateApplicationTest]: src/test/java/uk/nhs/hee/tis/template/TemplateApplicationTest.java
