# F1 Web API

## Description

This is a TypeScript API for building a web API using the Fastify framework. The API provides information about Formula 1 teams and drivers.

## Domain

The API provides data related to the Formula 1 world, including details about participating teams and drivers.

## Features

- Get a list of Formula 1 teams.
- Get a list of Formula 1 drivers.
- Get details of a specific driver by ID.

## Implementation

The API was developed using TypeScript and the Fastify framework. The data is provided statically, simulating information about Formula 1 teams and drivers.

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/joaopedrolessa/node-ts-minimal-webapi-fastify.git
cd f1-webapi
```

2. Install the dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm run start:dev
```

4. Access the API endpoints as needed.

## Technology Used

- [Fastify](https://www.fastify.io/): Fast, low overhead web framework for Node.js.
- [@fastify/cors](https://github.com/fastify/fastify-cors): Fastify plugin for handling CORS (Cross-Origin Resource Sharing) headers.
- [TypeScript](https://www.typescriptlang.org/): Superset of JavaScript that adds optional static typing to JavaScript.
- [Tsup](https://github.com/egoist/tsup): TypeScript bundling tool.

## License

This project is licensed under the ISC License. See the [LICENSE](LICENSE) file for details.