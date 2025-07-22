# User Auth App

A simple Node.js + Express + MongoDB backend for user registration and login.

## Setup

1. Install dependencies:
   ```
   npm install
   ```

2. Create `.env` file:
   ```
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

3. Run the server:
   ```
   node server.js
   ```

## Routes

- POST `/api/auth/register`
- POST `/api/auth/login`
