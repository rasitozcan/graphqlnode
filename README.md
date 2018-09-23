# hackernews-graphql-js

Hackernews api mainly based on the instructions on (https://www.howtographql.com/). I have decided to use a local db (mySQL) instead of demo db of Prisma which is preferred in the tutorial.

## Usage

### 1. Clone repository & install dependencies

```sh
git clone https://github.com/rasitozcan/graphqlnode.git
cd graphqlnode
yarn install # or `npm install`
```

### 2. Run database as docker deamon

```sh
cd database
docker-compose up -d
```

Your Prisma server will start running on http://localhost:4466 which means you can now start deploying Prisma services to it using the Prisma CLI.

### 3. Deploy the Prisma database service

Assuming you have Docker installed and already completed step 2, deploy Prisma locally by Creating a new database.

```sh
yarn prisma deploy
```

### 3. Start the server & open Playground

To interact with the API in a GraphQL Playground, all you need to do is execute the `dev` script defined in `package.json`:

```sh
yarn dev
```
