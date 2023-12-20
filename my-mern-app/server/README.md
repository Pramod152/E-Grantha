# Server

This is the server side of our MERN application.

## Setup

1. Navigate to the server directory: `cd server`
2. Install the dependencies: `npm install`
3. Start the server: `npm start`

## Environment Variables

The server uses the following environment variables:

- `DB_CONNECTION`: Your MongoDB connection string
- `PORT`: The port on which the server should run

These are stored in the `.env` file.

## Structure

- `src/app.js`: This is the main file of the server. It sets up the server and any middleware.
- `src/models`: This directory contains the Mongoose models, which represent the data in the MongoDB database.
- `src/routes`: This directory contains the Express routes, which define the endpoints of the API.
- `src/controllers`: This directory contains the Express controllers, which handle the logic for the routes.

## Dependencies

The server has the following main dependencies:

- `express`: A web application framework for Node.js
- `mongoose`: A MongoDB object modeling tool
- `dotenv`: A zero-dependency module that loads environment variables from a `.env` file into `process.env`
- `cors`: A package for providing a Connect/Express middleware that can be used to enable CORS with various options.

Remember to always keep your `.env` file secure and never push it to a public repository.