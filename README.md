# Login and Signup Application

A simple login and signup application built with React and Node.js Express.

## Features

- User signup with name, email, and password
- User login with email and password
- Password hashing with bcrypt
- Responsive design

## Installation

### Backend

```bash
npm install
npm run server
```

### Frontend

```bash
cd client
npm install
npm start
```

## Running the Application

1. Start the backend server:
   ```bash
   npm run server
   ```

2. In a new terminal, start the React frontend:
   ```bash
   cd client
   npm start
   ```

The backend runs on `http://localhost:5000` and the frontend on `http://localhost:3000`.

## API Endpoints

- `POST /api/signup` - Register a new user
- `POST /api/login` - Login an existing user
