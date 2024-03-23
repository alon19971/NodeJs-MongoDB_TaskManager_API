# Personal Task Manager API

## Overview

The Personal Task Manager API is designed as the backend for a task management application, enabling users to efficiently manage their tasks through comprehensive CRUD (Create, Read, Update, Delete) operations. This robust API is built using Node.js and MongoDB, incorporating Express.js for streamlined server functionality and Mongoose for elegant database interaction. Security is paramount, with JWT authentication ensuring protected access to the application's features.

## Features

- **JWT Authentication:** Supports secure signup and login processes.
- **Task Management:** Enables users to create, view, update, and delete tasks.
- **User Management:** Allows for user registration, profile updates, and account deletion.
- **Query Support:** Offers the ability to filter tasks by various criteria, such as status or due date.

## Built With

- **Node.js** - The runtime server environment.
- **Express.js** - The web framework used.
- **MongoDB** - The NoSQL database employed.
- **Mongoose** - Object modeling tool for MongoDB.
- **JWT** - Utilized for secure authentication.

## API Documentation

### Authentication

- `/signup`: Register a new user.
- `/login`: Log in for existing users.

### Tasks

- CRUD Operations: Manage tasks through the `/tasks` endpoint.

### Categories

- CRUD Operations: Organize tasks into categories via the `/categories` endpoint.

## Usage

1. **Sign Up:** Register for a new user account using the `/signup` endpoint.
2. **Log In:** Authenticate with the `/login` endpoint to receive a JWT for accessing protected routes.
3. **Manage Tasks:** Utilize the `/tasks` endpoint to perform CRUD operations on tasks.
4. **User Management:** Access the `/users` endpoint to manage user account details.

## Getting Started

To get a local copy up and running follow these simple steps:

1. Clone the repository to your local machine.
2. Install the necessary dependencies by running `npm install`.
3. Ensure MongoDB is running on your local machine or set up a MongoDB Atlas cluster.
4. Create a `.env` file in the root directory and set your environment variables (e.g., `JWT_SECRET_KEY`).
5. Start the server with `npm start` or `nodemon` if you're in a development environment.
