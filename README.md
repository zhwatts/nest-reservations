# Nest JS Microservice, Build and Deploy a Scaleable Backend

This project represents work at various stages as I progress through the Nest JS Micro Services, Build and Deploy a scaleable backend, as taught by **Michael Guay**

```
https://udemy.com/course/nestjs-microservices-build-deploy-a-scaleable-backend
```

> NestJS is an incredible backend framework that allows us to build scaleable Node.js backends with very little complexity. A microservice architecture is a popular architecture that allows us to build & deploy several independent applications that communicate with each other via a chosen transport layer.
>
> This course is designed to bridge the gap between NestJS & this microservice architecture. It goes beyond the NestJS documentation to show you how to build a real reservation booking system that accepts payments, sends email notifications, and persists data to a MongoDB, Postgres & MySQL database.
>
> Here are just some of the few additional things you can expect to learn in this course:
>
> - Develop a productionized Dockerfile for NestJS microservice
> - Create a monorepo & shared library for common code
> - Learn how to create a custom package.json & Dockerfile for each microservice
> - Automate the build & deployment of Dockerfiles with a custom CI/CD process
> - Connect microservices together using a TCP transport layer
>
> By the end of this course, you will know how to build, deploy & test Nestjs Microservices so you can create any scaleable application that you can think of.

## Notes

Special notes about how this repo may differ from the course

- Work prior to 2-11 (Validation & Logging) was not version controlled
- I chose to run the dockerized version of mongo DB from the beginning. Following this documentation to get started [https://www.mongodb.com/docs/manual/tutorial/install-mongodb-community-with-docker]()

## Installation

```bash
$ pnpm install
```

## Running the app

```bash
# development
$ pnpm run start

# watch mode
$ pnpm run start:dev

# production mode
$ pnpm run start:prod
```

## Test

```bash
# unit tests
$ pnpm run test

# e2e tests
$ pnpm run test:e2e

# test coverage
$ pnpm run test:cov
```
