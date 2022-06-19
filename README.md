# Periodic Tables: A Full-Stack Restaurant Reservation Solution.

Periodic Tables is a full-stack solution to a full-stack problem: managing table reservations at a restaurant!
Built to support CRUDL operations, this is a simple and effective application for corporate usage.
A company can both create reservations for their customers, as well as service tables as need be.
Status updates are provided throughout, and when a table is finished dining, it can be cleared.

This application was built with the following tools:
Front-End: React.js, Bootstrap, HTML, CSS
Back-End: Express.js, Node.js, Knex, PostgreSQL
Deployment & Version Control: Git, GitHub, Heroku

Deployed Version of the Application can be found here: https://order-up-client.vercel.app/dashboard

## Database setup

Set up four new ElephantSQL database instances - development, test, preview, and production - by following the instructions in the "PostgreSQL: Creating & Deleting Databases" checkpoint.

After setting up your database instances, connect DBeaver to your new database instances by following the instructions in the "PostgreSQL: Installing DBeaver" checkpoint.

### Knex

Run `npx knex` commands from within the `back-end` folder, which is where the `knexfile.js` file is located.

## Installation

Fork and clone this repository.
Run `cp ./back-end/.env.sample ./back-end/.env`.
Update the `./back-end/.env` file with the connection URL's to your ElephantSQL database instance.
Run `cp ./front-end/.env.sample ./front-end/.env`.
You should not need to make changes to the `./front-end/.env` file unless you want to connect to a backend at a location other than `http://localhost:5001`.
Run `npm install` to install project dependencies.
Run `npm run start:dev` to start your server in development mode.

If you have trouble getting the server to run, reach out for assistance.

## Running tests

This project has unit, integration, and end-to-end (e2e) tests.
Test are split up by user story. You can run the tests for a given user story by running:
`npm run test:X` where `X` is the user story number.
You can aditionally run tests by running
`npm run test:backend` or
`npm run test:frontend`.
These work for the corresponsing user story commands for these extensions as well.
