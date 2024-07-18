# Ecommerce Application

## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.
Deploying the backend service of an Ecommerce Application using NestJS.

## Installation

```bash
$ npm install
```

## Prepare database

Run docker container of postgres db
```bash
$ docker compose up -d
```

Run migration
```bash
$ npm run migration:run
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

