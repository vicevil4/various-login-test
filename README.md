# various-login-test

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Implement various login authentication processes.

## Tools

- [Node.js 16.x](https://nodejs.org/ko/download/package-manager/#macos)
- [OpenJDK 11](https://openjdk.org/projects/jdk/11/)
- [Spring Boot 2.7.1](https://spring.io/projects/spring-boot)
- [Spring Boot CLI 2.7.1](https://docs.spring.io/spring-boot/docs/2.7.1/reference/html/cli.html)

## Prepare

### Install OpenJDK

```shell
# https://formulae.brew.sh/formula/openjdk@11
> brew install openjdk@11
> java -version
openjdk version "11.0.6" 2020-01-14
OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.6+10)
OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.6+10, mixed mode)
```

### Initialzr Spring Boot Backend Server

```shell
# https://start.spring.io/
> spring init --build=maven --java-version=11 --force \
    --boot-version=2.7.1 \
    --dependencies=webflux,devtools,h2,actuator \
    --groupId=io.vicevil4 \
    --artifactId=vlogin \
    --name=vlogin-server \
    --package-name=io.vicevil4.vlogin \
    --description="vlogin server" \
    --packaging=jar \
    vlogin-server.zip
```

## Build & Run

## Development
