- **Name**: Saloni Shaw
- **Roll No.**: 22CE10065
- **University**: IIT Kharagpur
- **Department**: Civil Engineering

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
#### 1. Clone the repository:
```
git clone https://github.com/saloni210804/live-chat-app.git
cd live-chat-app
```
#### 2. Install dependencies for both client and server:
Navigate to the server directory
```
cd live-chat-server
npm install
```
Navigate to the client directory
```
cd ../live-chat-client
npm install
```
####  3. Create an environment configuration for the backend:
Navigate to the server directory
```
cd live-chat-server
```
Create a .env file with the following content:
```
MONGO_URI=<<paste the MongoDB URL here>>
JWT_SECRET=<<set your JWT secret key>>
PORT=8080
```

####  4. Install backend dependencies:
```
npm install express socket.io mongoose bcrypt jsonwebtoken dotenv cors
```
#### 5. Start the MongoDB server and Backend:
Make sure MongoDB is running and connected via the URL in the .env file
```
npm run start
```
####  6. Navigate to the frontend directory and install frontend dependencies:
```
cd live-chat-client
npm install react react-dom redux react-redux @reduxjs/toolkit axios @mui/material @emotion/react @emotion/styled socket.io-client framer-motion
```
####  7. Start the frontend server:
```
npm start
```
# Installed Dependencies**
**Backend Dependencies:**
- express: For handling HTTP requests
- socket.io: For real-time communication
- mongoose: For MongoDB interactions
- bcrypt: For password encryption
- jsonwebtoken: For creating and validating JWT tokens
- dotenv: For managing environment variables
- cors: For handling Cross-Origin Resource Sharing (CORS)
- Frontend Dependencies:
- react: For building the user interface
- redux: For state management
- @mui/material: For UI components
- axios: For making HTTP requests to the backend
- socket.io-client: For real-time communication with the backend
- @reduxjs/toolkit: For simplifying Redux setup
- framer-motion: For adding animations
