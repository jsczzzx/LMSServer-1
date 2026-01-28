# Express.js Demo App

A minimal Express.js demo application for quick setup and development.

## Features

-   Express.js server
-   Basic REST endpoints
-   JSON request parsing
-   Nodemon for development

## Prerequisites

-   Node.js 18+
-   npm

## Installation

``` bash
npm install
```

## Running the App

### Development

``` bash
npm run dev
```

### Production

``` bash
npm start
```

## Available Endpoints

-   GET `/health` --- Health check
-   GET `/api/hello` --- Demo endpoint
-   POST `/api/echo` --- Echo request body

## Project Structure

    src/
      app.js

## Notes

This project is intended as a lightweight starting point and can be
extended with routing, authentication, or TypeScript as needed.
