# MERN Chat App

A real-time chat application built with the MERN stack (MongoDB, Express.js, React, and Node.js) featuring Socket.io for instant messaging.

live demo: https://mern-chat-app-x01f.onrender.com/login

## Features

- Real-time messaging with Socket.io
- User authentication (login/registration)
- Online status indicators
- Responsive design for all devices
- One-to-one chat functionality
- Message timestamps
- Typing indicators
- Message history persistence

## Technologies Used

- **Frontend**: React.js, Socket.io-client, Axios, React Router, Context API
- **Backend**: Node.js, Express.js, Socket.io, JSON Web Tokens (JWT)
- **Database**: MongoDB (with Mongoose ODM)
- **Styling**: CSS (or your preferred styling solution)

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js (v14 or later)
- npm or yarn
- MongoDB Atlas account or local MongoDB installation

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/dLomas26/mern-chat-app.git
   cd mern-chat-app

2. Install dependencies for both server and client:
 
  # Install server dependencies
  cd server
  npm install
  
  # Install client dependencies
  cd ../client
  npm install

3. Set up environment variables:

Create a .env file in the server directory with the following variables:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
PORT=5000

4. Start the application:

# From the project root directory:

# Start the server (in one terminal)
cd server
npm start

# Start the client (in another terminal)
cd ../client
npm start
