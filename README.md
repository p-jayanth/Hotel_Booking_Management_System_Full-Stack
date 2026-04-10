Hotel Booking Management System (MERN Stack)

Project Overview

This is a full-stack Hotel Booking Management System built using the MERN stack (MongoDB, Express, React, Node.js). The application allows users to register, log in, browse available hotels, and make bookings. It demonstrates real-world implementation of authentication, API integration, and database management.

Features
  User Authentication (JWT-based login & registration)
  View and browse hotels
  Booking system for rooms
  REST API integration between frontend and backend
  Responsive UI using React and Bootstrap
  Tech Stack
  
Frontend
    React.js
    HTML, CSS
    Bootstrap
    Axios
    
Backend
    Node.js
    Express.js
    JWT Authentication
    Database
    MongoDB
    Mongoose
    
Project Structure
Hotel_Booking_Management_System/
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── server.js
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.js
│   └── package.json
│
└── README.md

Installation & Setup
    Prerequisites

Make sure you have:
    Node.js installed
    MongoDB (local or MongoDB Atlas)
    Git installed

Step 1: Clone the Repository
    git clone https://github.com/p-jayanth/Hotel_Booking_Management_System_Full-Stack.git
    cd Hotel_Booking_Management_System_Full-Stack

Step 2: Install Dependencies
    Backend
    cd backend
    npm install
    Frontend
    cd ../frontend
    npm install
    
Step 3: Environment Variables
    Create a .env file inside the backend folder:
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_secret_key
    PORT=5000
    
Step 4: Run the Application
    Start Backend Server
    cd backend
    npm start
    Start Frontend
    cd frontend
    npm start

Step 5: Access the Application
    Frontend → http://localhost:3000
    Backend API → http://localhost:5000
    
Authentication Flow
    User registers/logs in
    Backend generates JWT token
    Token is stored in frontend
    Token is sent in API requests
    Backend verifies token before allowing access
    
API Endpoints
    Feature	Endpoint
    Auth	/api/auth
    Hotels	/api/hotels
    Rooms	/api/rooms
    Bookings	/api/bookings

Future Improvements
    Payment integration
    Booking history dashboard
    Admin panel
    Real-time availability



BACKEND

to create and connect to backend create .env and .env.txt in the backend folder in .env.txt enter the port in which backend you want to connect and in .env give PORT= port number, MONGO_URI= YOUR MONGO DB ATLAS URL, JWT_SCRETE_KEY= RANDOM LETTERS MAY INCLUCE NUMBERS, TO RUN GO TO THE DIRECTORY AND TYPE npm start run-dev to start the server

