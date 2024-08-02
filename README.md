# User Management System

This project is a full-stack application built with the MERN stack (MongoDB, Express.js, React, Node.js). It includes user registration and login functionalities with JWT authentication.

## Project Structure

- **client/**: React frontend
- **server/**: Express backend

### Frontend (`client`)

- **src/components/auth/Register.js**: Registration form component
- **src/components/auth/Login.js**: Login form component
- **src/context/AuthContext.js**: Context for authentication state
- **src/context/AuthState.js**: Authentication state management
- **src/context/authreducer.js**: Reducer for authentication state
- **src/context/types.js**: Action types for authentication
- **src/App.js**: Main application component with routing
- **src/index.js**: Entry point for the React application

### Backend (`server`)

- **server/config/db.js**: MongoDB connection setup
- **server/models/User.js**: Mongoose schema for the user
- **server/routes/auth.js**: Authentication routes
- **server/middleware/authMiddleware.js**: Middleware for JWT authentication
- **server/controllers/authController.js**: Controller functions for user registration, login, and retrieval
- **server/server.js**: Main server file
- **server/.env**: Environment variables file

## Prerequisites

- Node.js (>=14.0.0)
- MongoDB
- npm or yarn

## Setup

### Backend Setup

1. **Navigate to the `server` directory**:
   ```bash
   cd server
