# GufGaf Chat App

GufGaf is a real-time chat application that enables users to communicate with each other through a modern and secure platform. The backend is built using Node.js and Express and is designed to handle RESTful API requests, while the frontend is developed with React. This application allows users to register, log in, send messages, and much more.

## Backend Features

- RESTful API with endpoints for user authentication and message handling.
- WebSocket implementation using Socket.io for real-time bidirectional communication.
- HTTPS for secure data transmission.
- Winston for logging.
- dotenv for environment variable management.
- CORS for cross-origin resource sharing.
- MongoDB integration for data persistence.
- Multiavatar API integration for generating user avatars.

## Frontend Features

- React-based user interface.
- Real-time messaging with Socket.io client.
- State management using React Context API or Redux.
- Responsive design for various screen sizes.

## Backend API Endpoints

- `POST /api/auth/login`: Authenticate a user.
- `POST /api/auth/register`: Register a new user.
- `POST /api/auth/logout`: Log out a user.
- `GET /api/auth/allusers`: Retrieve all users.
- `POST /api/messages/addmsg`: Send a new message.
- `GET /api/messages/getmsg`: Retrieve messages.
- `POST /api/auth/setavatar`: Set a user's avatar.

## Getting Started

To get the backend running locally:

1. Clone the backend repository:

```bash
git clone https://github.com/prof-gautam/gufgaaf_backend.git
cd gufgaaf_backend

```


## Backend Setup

### Install dependencies

Run the following command to install all necessary dependencies for the backend:

```bash
npm install
```


cp .env.example .env

# Then edit the .env file with your specific configuration


## Start the Backend Server

Once the dependencies are installed and environment variables are set, you can start the backend server with:

```
npm start

```
