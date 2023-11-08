# Nodejs-Blog-Backend-and-Frontend


Overview
This project consists of two Node.js applications: a backend API and a frontend web app. The backend API is responsible for managing a collection of blog posts, including creating, reading, updating, and deleting posts. The frontend web app allows users to view, create, and edit posts.

Backend API
The backend API is built using Express.js and is exposed on port 4000. It provides the following endpoints:

GET /posts: Retrieves a list of all posts
GET /posts/:id: Retrieves a specific post by ID
POST /posts: Creates a new post
PATCH /posts/:id: Updates an existing post
DELETE /posts/:id: Deletes an existing post
Frontend Web App
The frontend web app is built using EJS and is served on port 3000. It provides the following features:

A homepage listing all posts
A form for creating new posts
A form for editing existing posts
Technologies Used
Node.js
Express.js
EJS
Axios
Body Parser
Steps to Run
To run the project, follow these steps:

Open two terminal windows.
In the first terminal window, navigate to the backend API directory and run the following command: node index.js.
In the second terminal window, navigate to the frontend web app directory and run the following command: node server.js.
Open a web browser and navigate to http://localhost:3000 to view the frontend web app.
