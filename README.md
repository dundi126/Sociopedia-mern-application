# FullStack Social Media App

This repository contains the source code for NodeLink a Social Media Application built using the MERN Stack (MongoDB, Express.js, ReactJs, and Node.js). This project demonstrates the implementation of a scalable and robust web application that supports user authentication, post creation, and basic social media interactions like commenting and liking.

🛠 Features

- User Authentication
  Secure login and registration with JWT-based authentication.
- Post Management
  Create, edit, and delete posts. Posts are stored in a MongoDB database.
- Commenting and Likes
  Engage with posts by commenting and liking.
- Responsive UI
  Built using react for a smooth and interactive user experience.
- Backend APIx
  A RESTful API powered by Express.js and Node.js.

📚 Tech Stack

- Frontend: ReactJS
- Backend: Node.js
- Database: MongoDB
- Authentication: JSON Web Tokens (JWT)
- Styling: Bootstrap/CSS

Follow these steps to run the application locally:

# Prerequisites

Ensure you have the following installed:

- Node.js
- ReactJS
- MongoDB

# Installation

Install dependencies for both frontend and backend: 
  - Backend dependencies
    cd backend
    npm install

  - Frontend dependencies
    cd ../frontend
    npm install
Start MongoDB locally or configure a MongoDB Atlas instance.

Set up environment variables:
Create a .env file in the backend folder:
- PORT=3000
- MONGO_URI=mongodb://localhost:27017/socialmediaJWT_SECRET=your-secret-key

# Run the application:

Start backend
- cd backend
- npm start

Start frontend
- cd ../frontend
- npm run dev
- Open your browser and navigate to http://localhost:4200.
