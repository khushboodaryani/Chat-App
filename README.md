MERN Chat Application

A real-time chat application built using the MERN stack. This app allows users to send and receive messages in real time, with features like user authentication, chat rooms, and message persistence.

Technologies Used

MongoDB - NoSQL database for storing user data and messages.
Express - Node.js web application framework for building the API.
React.js - Frontend framework for building the user interface.
Node.js - JavaScript runtime environment for the server-side application.
Socket.io - Library for enabling real-time, bidirectional communication between the client and server.
JWT (JSON Web Tokens) - For user authentication and authorization.
Features

Real-time messaging with Socket.io.
User authentication with JWT.
Persistent message storage in MongoDB.
User profiles and the ability to join different chat rooms.
Responsive UI built with React and styled with CSS.
Installation

Backend (Node.js/Express)
Clone the repository:
git clone https://github.com/your-username/mern-chat-app.git
Navigate to the backend directory:
cd mern-chat-app/backend
Install the dependencies:
npm install
Create a .env file in the backend directory with the following environment variables:
MONGO_URI=mongodb://localhost:27017/chat-app
JWT_SECRET=your_jwt_secret
PORT=5000
Run the backend server:
npm run server
The backend server should now be running on http://localhost:5000.

Frontend (React.js)
Navigate to the frontend directory:
cd mern-chat-app/frontend
Install the dependencies:
npm install
Run the React development server:
npm run dev
The frontend application should now be running on http://localhost:3000.

Usage

Open http://localhost:3000 in your browser.
Log in with your credentials or register if you're a new user.
Join a chat room and start chatting in real-time.
Messages are stored in the MongoDB database, and they will persist even after a page refresh.
