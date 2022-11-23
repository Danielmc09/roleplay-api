# Adonis API application rolePlay

This app creates users and groups, users can request to join a group, the request can be accepted or rejected, users can be removed from groups

## Clone the repository

```bash
https://github.com/Danielmc09/roleplay-api.git
```

1. create the .env file in the project root based on the .env.example file in order to set the environment variables
2. run adonis key:generate

use the node command to install the dependencies

```bash
npm install
```
## Note 

- the database used for the tests is Sqlite3
- the database used for the project is Postgres
- collection is attached in insomnia to import and test

### Migrations

Run the following command to run startup migrations.

```js
node ace migration:run
```

### Test

Run the following command to run test.

```js
yarn test
```

### Run API application
```js
yarn dev
```

- Ports to use that should not be busy or with local services turned off:
  - Postgres: 5432 
  - AdonisJS: 3333


Autor: Angel Daniel Menideta Castillo © 2022
