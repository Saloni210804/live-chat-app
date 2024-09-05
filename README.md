**Name**: Saloni Shaw
**Roll No.**: 22CE10065
**University**: IIT Kharagpur
**Department**: Civil Engineering

# Live Chat Application

This is a real-time messaging application that allows users to engage in one-on-one or group chats. Built using **React** on the frontend and **Node.js/Express** on the backend, it leverages **Socket.io** for real-time communication and **MongoDB** for data persistence.

---

## **Features**
- User authentication (JWT-based).
- Real-time messaging with **Socket.io**.
- One-on-one and group chat functionality.
- Light and Dark theme modes.
- Responsive UI using Material-UI (MUI).
- Fully protected routes using JWT tokens.

---

## **Tech Stack**
- **Frontend**: React, Redux, Axios, Material-UI, Socket.io-client
- **Backend**: Node.js, Express, MongoDB, Mongoose, JWT, Bcrypt
- **Real-Time Communication**: Socket.io
- **Database**: MongoDB

---

## **Setup and Installation**

### **Prerequisites**

Before running this app, make sure you have the following installed:
- **Node.js** 
- **MongoDB** 

### **Steps to Run Locally**

1. **Clone the repository**:

   ```bash
   git clone https://github.com/saloni210804/live-chat-app.git
   cd live-chat-app

2. **Install dependencies for both client and server**:

Navigate to the server and client directory and install the dependencies:

cd live-chat-server
npm install

cd ../live-chat-client
npm install

3. **Environment Configuration**

Create a .env file in the live-chat-server directory with the following content:

MONGO_URI=<<paste the url>>
JWT_SECRET=<<set a jwt key>>
PORT=8080

5. **For the Backend Server**:

# Navigate to the backend directory
cd live-chat-server

# Install backend dependencies
npm install express socket.io mongoose bcrypt jsonwebtoken dotenv cors

express             # For handling HTTP requests
jsonwebtoken        # For creating and validating JWT tokens
bcrypt              # For password encryption and validation
mongoose            # For interacting with MongoDB
socket.io           # For enabling real-time messaging
dotenv              # To manage environment variables securely


6. **For Frontend/Client**

# Navigate to the frontend directory
cd ../live-chat-client

# Install frontend dependencies
npm install react react-dom redux react-redux @reduxjs/toolkit axios @mui/material @emotion/react @emotion/styled socket.io-client framer-motion

react               # For building the user interface
redux               # For state management
@mui/material       # For building modern UI components
axios               # For making API requests to the backend
socket.io-client    # For real-time communication between client and server
@reduxjs/toolkit    # Simplifies Redux setup

7. **Run the application**

# Start MongoDB (make sure MongoDB is running locally):
mongod

# Start the Backend:
cd live-chat-server
npm run start

# Start the Frontend:
cd ../live-chat-client
npm start
