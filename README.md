# NestJS Final Test Project

This project is a NestJS application with end-to-end tests using MongoDB. This guide will help you set up the project, run the application, and execute tests.

## Prerequisites

- [Node.js](https://nodejs.org/) (version 12.x or higher)
- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/BelkacemRedouane/nestjs-final-test.git
    cd nestjs-final-test
    ```

2. Install dependencies:

    ```bash
    npm ci
    ```

## Running the Application

### Using MongoDB

#### On Windows

1. Start the application with MongoDB:

    ```bash
    npm run start:mongodb:windows
    ```

    This will set the `DBMS` environment variable to `mongodb`, start the MongoDB container, and launch the application in development mode.

#### On Linux

1. Start the application with MongoDB:

    ```bash
    npm run start:mongodb:linux
    ```

    This will set the `DBMS` environment variable to `mongodb`, start the MongoDB container, and launch the application in development mode.

## Running End-to-End Tests

### Using MongoDB

#### On Windows

1. Run the end-to-end tests with MongoDB:

    ```bash
    npm run test:e2e:mongodb:windows
    ```

    This will set the `DBMS` environment variable to `mongodb`, start the MongoDB container, and execute the tests.

#### On Linux

1. Run the end-to-end tests with MongoDB:

    ```bash
    npm run test:e2e:mongodb:linux
    ```

    This will set the `DBMS` environment variable to `mongodb`, start the MongoDB container, and execute the tests.

## Environment Variables

Make sure to configure your `.env` file with the appropriate settings for your database and other environment variables.

## Package Scripts

Here is a summary of the available npm scripts:

- **Clone the repository:**
    ```bash
    git clone https://github.com/BelkacemRedouane/nestjs-final-test.git
    cd nestjs-final-test
    ```
- **Install dependencies:**
    ```bash
    npm ci
    ```
- **Start the application with MongoDB (Windows):**
    ```bash
    npm run start:mongodb:windows
    ```
- **Start the application with MongoDB (Linux):**
    ```bash
    npm run start:mongodb:linux
    ```
- **Run end-to-end tests with MongoDB (Windows):**
    ```bash
    npm run test:e2e:mongodb:windows
    ```
- **Run end-to-end tests with MongoDB (Linux):**
    ```bash
    npm run test:e2e:mongodb:linux
    ```

---

This README provides detailed instructions for setting up, running, and testing your NestJS project with MongoDB, including commands for both Windows and Linux platforms.

---


