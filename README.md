# Task Management Application - Backend

This is the backend API for a task management application. It's built with Node.js and Express, and uses MongoDB as the database.

## Prerequisites

- Node.js (v14.0.0 or later)
- npm (v6.0.0 or later)
- MongoDB Atlas account

## Installation

1. Clone the repository:

git clone https://github.com/your-username/task-manager-server.git
cd task-manager-server

2. Install dependencies:

npm install

3. Create a `.env` file in the root directory and add the following:

MONGODB_URI=your_mongodb_atlas_connection_string
PORT=3001

Replace `your_mongodb_atlas_connection_string` with your actual MongoDB Atlas connection string.

## Running the Application

To start the server in development mode:

npm run dev

For production:

npm start

The server will start on the port specified in your `.env` file (default is 3001).

## API Endpoints

- `GET /api/tasks`: Get all tasks
- `POST /api/tasks`: Create a new task
- `PUT /api/tasks/:id`: Update a task
- `DELETE /api/tasks/:id`: Delete a task

## Database

This application uses MongoDB Atlas as its database. Make sure you have set up a MongoDB Atlas account and have the connection string ready.

## Deployment

This backend is configured for deployment on Render. To deploy:

1. Push your changes to your GitHub repository.
2. Create a new Web Service on Render.
3. Connect your GitHub repo to Render.
4. Add the `MONGODB_URI` environment variable in Render's settings.
5. Deploy the application.

## Technology Stack

- Node.js
- Express
- MongoDB
- Git (Version Control)



