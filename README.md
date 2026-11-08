# Node.js Authentication System

A user authentication system built using **Node.js, Express.js, MongoDB, Mongoose, EJS, and Tailwind CSS**.

## Features

- User Registration
- User Login
- Password Hashing using Bcrypt
- JWT Token Generation
- Cookie Management using Cookie Parser
- User Logout
- MongoDB Database Integration
- EJS Templating
- Tailwind CSS Styling

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose
- EJS
- Bcrypt
- JSON Web Token (JWT)
- Cookie Parser
- Tailwind CSS

## Installation

1. Clone the repository:

```bash
git clone YOUR_REPOSITORY_URL
```

2. Navigate to the project directory:

```bash
cd YOUR_PROJECT_FOLDER
```

3. Install dependencies:

```bash
npm install
```

4. Start MongoDB on your system.

5. Run the application:

```bash
node app.js
```

Or using Nodemon:

```bash
nodemon app.js
```

6. Open your browser:

```text
http://localhost:3000
```

## Authentication Flow

1. Register a new user with username, email, password, and age.
2. Password is hashed using Bcrypt before storing it in MongoDB.
3. JWT token is generated after registration.
4. Login verifies the password using Bcrypt.
5. A JWT token is generated and stored in a cookie after successful login.
6. Logout clears the authentication cookie.

## Learning Objectives

- Understanding Authentication and Authorization
- Learning Password Hashing
- Understanding JWT
- Working with Cookies
- Connecting Express.js with MongoDB
- Building Login and Registration Systems

## Author

**Ashik**

GitHub: [ashik-210](https://github.com/ashik-210)
