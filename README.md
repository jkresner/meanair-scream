# SCREAMjs

## Testing Node.js apps

Testing real-world scenarios and data is cumbersome. Setting up and replaying 
conditions with many users and long work flows requires lots of vanilla JS code.

SCREAM helps you write and stay on top of terse, legible and maintainable tests. 

## Safely execute tasks

Migrations

## Flags

## Features

1. Execute efficiently

- STUB conventions
- Disable stun flag

2. Seed data 

- Currently support using MongoDB .bson files

- Mix and match .coffee & .js from one spec to another

- FIXTURE conventions

- HTTP session & login conventions

## Setup

1. [node v8+](https://nodejs.org/download/)
2. [mongodb v3+](https://www.mongodb.org/downloads)
3. `npm install`

## 4 example apps with SCREAMjs tests

##### **ex1** simple console app

`npm run-script ex1`

- js tests
- example SCREAM folder structure
- empty `scream.json` config

##### **ex2** express/mongodb app

`npm run-script ex2`

- coffee tests
- `scream.json` config with mongodb config

##### **ex3** mongodb data bootstrap,

`npm run-script ex3`

- Both coffee & js tests 
- Bootstrap db.Users collection from users.bson file before tests run
- FIXTURE.users 

##### **ex4** express/mongodb/passport app

`npm run-script ex4`

- coffee tests 
- LOGIN changes current users
- PAGE tests expected 200


## Tests

`npm test`
