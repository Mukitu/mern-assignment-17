# Assignment 17 - Express.js & MongoDB CRUD API

A secure backend application built with Node.js, Express.js, and MongoDB Atlas. It features JWT-based authentication and full user management CRUD operations.

## Features
- User Registration & Login (Password hashing via Bcrypt)
- JWT Authentication Middleware (Protected Routes)
- Complete CRUD Operations (Fetch, Update, Delete Users)
- Cloud Database Integration with MongoDB Atlas

## Getting Started j

1. Clone the project and install dependencies:
```bash
npm install

1. Create a .env file in the root directory:

PORT=5000
MONGO_URI=your_mongodb_atlas_connection_string
JWT_SECRET=your_jwt_secret_key

2. Run the server:
Bash
npm run dev

API Endpoints:

POST /api/register - User Registration
POST /api/login - User Login (Returns JWT Token)
GET /api/profile - Get User Profile (Protected)
GET /api/users - Get All Users
GET /api/users/:id - Get Single User
PUT /api/users/:id - Update User Name
DELETE /api/users/:id - Delete User
