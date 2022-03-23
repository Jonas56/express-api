# Express API

This is a RESTful API example based on express.js and PostgreSQL, following the MVC pattern i.e. Model View Controller.

Sequelize is used for Database transactions which is an elegant solution to postgresql relationnal modeling for node.js.

The application is production ready, and can be used behind a Nginx reverse proxy securely.

## Table of contents

- [Highlights](#highlights)
- [Endpoints](#endpoints)
- [Quick start](#quick-start)

## Highlights

- Modular RESTful API
- ES6 Classes
- Action based
- SQL based (PostgreSQL with Sequelize ORM)
- Migrations
- Pagination
- Auth (JWT/Access-token/Refresh-token)
- Request validation
- CRUD (users, books resources)
- Automated API documentation
- Full authentication/authorization and user registration flow implemented
- Tests (Integretion tests using **jest**)
- Heroku

## Endpoints

- `/register`
- `/login`
- `/books`
- `/collection`
- `/reading`

## Quick start

- Copy and fill out envirenement variables

```console
$ cp .env.example .env
    fill out envirenement variables
```

- Install dependencies

```console
$ npm install
```

- Run server on developpement

```console
$ npm run dev
```

- Visit [`localhost:3001`](http://localhost:3001)

### Tests

```console
$ npm run test
```

### Lint

```console
$ npm run lint
```

## Contributing

For contribution and feature requests, please create an [issue](https://github.com/Jonas56/express-api/issues) first.
