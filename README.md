# Dialogue Depot AI - Node.js Backend

Welcome to the backend of DialogueDepot AI, a robust chat platform with real-time messaging and AI-generated responses. This Node.js backend is responsible for handling server-side logic, API routes, and interactions with MongoDB.

## Table of Contents
- [Introduction](#introduction)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Setup](#setup)
- [API Endpoints](#api-endpoints)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## Introduction

DialogueDepot AI is a MERN stack (MongoDB, Express.js, React.js, Node.js) chat platform with Socket.IO for real-time communication. The backend integrates a Flask API with a pre-trained ML model for AI-generated responses.

## Tech Stack

- **Node.js and Express.js**: Backend server and API.
- **MongoDB**: NoSQL database for storing user data, chats, and messages.
- **JWT and Bcrypt**: User authentication and password hashing.
- **Socket.IO**: Real-time WebSocket communication.

## Project Structure

- **config/**: MongoDB configuration files.
- **controllers/**: Logic for handling API requests.
- **middleware/**: Middleware for authentication and error handling.
- **models/**: MongoDB models defining data structure.
- **routes/**: API routes for user, chat, and message operations.
- **server.js**: Entry point for the Node.js server.

## Setup

1. Clone the repository:
   ```bash
   git clone <https://github.com/imambujshukla7/dialoguedepotai-nodejs>
   cd dialogue-depot-nodejs
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

## API Endpoints

- **POST /api/user/signup**: User registration.
- **POST /api/user/login**: User login.
- **GET /api/user/search**: Search for users.
- **POST /api/chat**: Create a new chat.
- **GET /api/chat**: Fetch user chats.
- **POST /api/chat/group**: Create a group chat.
- **PUT /api/chat/rename**: Rename a group chat.
- **PUT /api/chat/groupremove**: Remove a user from a group.
- **PUT /api/chat/groupadd**: Add a user to a group.
- ... (and more)

## Deployment

The backend is deployed on render, [dialoguedepotai.site](https://dialoguedepotai.site) is the complete application.

## Contributing

We welcome contributions! Feel free to open issues, create pull requests, or provide feedback.

## License

This project is licensed under the [MIT License](LICENSE).
