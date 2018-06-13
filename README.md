# Star Wars example server

This is a really simple GraphQL server that uses [Apollo Server](https://github.com/apollostack/apollo-server) and [GraphQL Tools](https://github.com/apollostack/graphql-tools) to serve the Star Wars example schema from http://www.graphql.org.

## Installation

Clone the repository and run `npm install`

```
git clone https://github.com/apollographql/starwars-server
cd starwars-server
npm install
npm install --save apollo-server-express graphql-tools graphql@0.11.7 express body-parser
```
Note: this example doesn't work with last graphql package version.

## Starting the server

```
npm start
```

The server will run on port 8080. You can change this by editing `server.js`.

## Testing the API

GraphiQL: http://localhost:8080/graphiql | GraphQL endpoint: http://localhost:8080/graphql | Websocket endpoint: ws://localhost:8080/websocket
