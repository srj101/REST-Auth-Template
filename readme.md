# REST Authentication Template

> Authentication REST API Getting Started Template by SRJOY.

This is an simple authentication REST api template for my own personal use to get me up & running fast and easy

## Features

- Admin Role
- Cookie based authentication
- JWT Access Tokens
- Other user roles
- Login
- Register

## Usage

### ES Modules in Node

We use ECMAScript Modules in the backend in this project. Be sure to have at least Node v14.6+ or you will need to add the "--experimental-modules" flag.

Also, when importing a file (not a package), be sure to add .js at the end or you will get a "module not found" error

You can also install and setup Babel if you would like

### Env Variables

Create a .env file in then root and add the following

```
MONGO = your mongodb uri
JWT = your top secret jwt
```

### Install Dependencies

```
npm install
```

### Run

```
# Run backend (:5000)
npm start
```

## License

The MIT License

Copyright (c) 2022 SR JOY
