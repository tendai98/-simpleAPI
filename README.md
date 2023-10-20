# Simple Express.js API

The Simple Express.js API is a basic RESTful API built with Express.js
Its just a small project I worked on to see how Express.js works and whatyou can do with it

## Table of Contents

- [Getting Started](#getting-started)
- [Authentication](#authentication)
- [Error Handling](#error-handling)
- [Deploying on Heroku](#deploying-on-heroku)

## Getting Started

To use the Simple Express.js API, follow these steps:

1. Clone the repository:

   ```
   git clone https://github.com/tendai98/simpleAPI.git
   ```

2. Navigate to the project directory:

   ```
   cd simpleAPI
   ```

3. Install the required dependencies:

   ```
   npm install
   ```

4. Start the server:

   ```
   npm start
   ```

   The server will run on the default port 5000, or you can specify a different port using the `PORT` environment variable.

## Authentication

The API does not require authentication for basic data operations. It's designed for simplicity and can be used without the need for complex authentication mechanisms.

## Error Handling

The API provides basic error handling for various scenarios. If an error occurs, it will respond with an error message and a corresponding error code. The error codes are as follows:

- `0`: Success
- `-1`: An error has occurred

## Deploying on Heroku

You can easily deploy this API on Heroku or any other hosting service that supports Node.js applications. Follow the hosting service's documentation for deployment instructions. Don't forget to set the `PORT` environment variable to the desired port during deployment.
