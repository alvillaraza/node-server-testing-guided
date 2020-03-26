# Web API Testing

## Objectives
- set up Jest for testing Node.js code
- write tests for API endpoints
- use Heroku Postgres in production

component(props) => UI;

function(args) => value;

endpoint(data) => response;

- run the server
- make a request
- inspect the response to check for assumptions



# steps for testing
npm i -g jest
yes to all questions

jest.config.js
  - "testEnvironment": "node"

pacakage.json
  -  under scripts:
  "test": "jest --watch"
  - manually add the following code to the bottom of the page:
    "jest": {
    "testEnvironment": "node"
  }

code the test
npm run test
npm i -D supertest
npm i -D jest