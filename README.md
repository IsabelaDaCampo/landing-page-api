# Landing Page API

This is the API to create the [React Avançado Landing Page](https://reactavancado.com.br/).

- API created with Strapi, GraphQL and Postgres.

## Requirements

This project uses [PostgreSQL](https://www.postgresql.org/), so, in order to make it working, install in your local machine or use Docker.

The configuration to the Database can be found on [config/database.js](config/database.js)

## Development

After cloning this project, install the dependencies:

```
yarn install
```

And run using:

```
yarn develop
```

The urls to access are:

- `http://localhost:1337/admin` - The Dashboard to create and populate data
- `http://localhost:1337/graphql` - GraphQL Playground to test your queries

The first time to access the Admin you'll need to create an user.

## Dump data

This project uses `Postgres` and if you want all the data previously, unzip the [data.zip](data.zip), copy the `uploads` folder to [public/uploads](public/uploads) and restore the data from the `local.dump` file inside the zip.

## Comandos para o Postgres
- sudo service postegresql status -> Verificar status do bd (on/off)
- sudo service postegresql start -> Iniciar bd
- sudo service postegresql stop -> Parar bd