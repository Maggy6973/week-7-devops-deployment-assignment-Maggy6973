
# My Frontend deployment link
https://week7frontend.vercel.app/
  ### I deployed it on vercel
  <img width="1354" height="663" alt="image" src="https://github.com/user-attachments/assets/26de0bcb-db05-48c2-8351-1a87e8a6a441" />

# My backend deployment link
https://week7-twil.onrender.
   ### I deployed it on Render
<img width="1355" height="664" alt="image" src="https://github.com/user-attachments/assets/b20f42ca-f711-4bb9-a7cd-d4e5c94e6207" />
<img width="1362" height="638" alt="image" src="https://github.com/user-attachments/assets/8dc7a40c-5706-4bfa-8e41-66c36e9f6f8c" />
<img width="1366" height="642" alt="image" src="https://github.com/user-attachments/assets/0089b7cf-b3c5-43c2-82d4-9fadbc3f963b" />


  ## I deployed it on Render
# User Authentication Application

This project is a user authentication application built with Express, React, and MongoDB. It allows users to register, log in, and access a dashboard with a welcome message.

## Project Structure

```
user-auth-app
├── backend
│   ├── src
│   │   ├── controllers
│   │   │   ├── authController.js
│   │   ├── models
│   │   │   ├── User.js
│   │   ├── routes
│   │   │   ├── authRoutes.js
│   │   ├── app.js
│   │   └── config
│   │       └── db.js
│   ├── package.json
│   └── README.md
├── frontend
│   ├── src
│   │   ├── components
│   │   │   ├── Dashboard.js
│   │   │   ├── LoginForm.js
│   │   │   └── RegisterForm.js
│   │   ├── App.js
│   │   ├── index.js
│   │   └── api
│   │       └── auth.js
│   ├── package.json
│   └── README.md
└── README.md
```

## Backend Setup

1. Navigate to the `backend` directory:
   ```
   cd backend
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Set up your MongoDB connection in `backend/src/config/db.js`.

4. Start the server:
   ```
   npm start
   ```

## Frontend Setup

1. Navigate to the `frontend` directory:
   ```
   cd frontend
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Start the React application:
   ```
   npm start
   ```

## API Endpoints

- **POST /api/register**: Register a new user.
- **POST /api/login**: Log in an existing user.

## Features

- User registration and login functionality.
- Dashboard with a welcome message after successful login or registration.

## Technologies Used

- Express.js
- React.js
- MongoDB
- Mongoose
- Node.js

## License

This project is licensed under the MIT License.
