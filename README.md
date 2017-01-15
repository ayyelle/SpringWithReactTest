# Spring Boot & ReactJS Demo

A simple demo app to demonstrate server side rendering with nashorn

## Requirements

* Java 8 JDK
* NodeJS

## How can I run it?

```bash
npm install
./gradlew bootRun
```

## Troubleshoot - Might also have to run the follow

```bash
npm install babel-core babel-loader --save-dev
npm install webpack -g
./gradlew run build
```
before 
```bash
./gradlew bootRun
```

open http://localhost:8080 in your browser.

