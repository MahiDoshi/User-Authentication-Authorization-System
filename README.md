# User Authentication & Authorization System

A secure backend-focused web application built with **Node.js**, **Express.js**, and **MongoDB Atlas** for user authentication, authorization, session handling, and role-based access control.

---

## 📌 Project Overview

This project implements a complete **User Authentication and Authorization System** using industry-standard security practices.

It allows users to register, log in, access protected routes, and perform role-based actions based on their assigned permissions. The system uses **JWT authentication**, **bcrypt password hashing**, **MongoDB Atlas** for database storage, and middleware-based route protection.

---

## 🚀 Features

- User registration and login
- JWT-based authentication
- Password hashing using bcrypt
- Role-based access control
- Protected routes and middleware
- Secure cookie management
- Environment variable configuration
- RESTful API architecture
- Postman API testing
- Simple frontend interface for demonstration

---

## 🛠️ Technology Stack

### Backend

- Node.js
- Express.js
- MongoDB Atlas
- Mongoose

### Security

- JSON Web Token
- bcrypt
- cookie-parser
- dotenv

### Frontend

- HTML
- CSS
- JavaScript

### Tools

- Postman
- Git
- GitHub

---

## ⚙️ How It Works

1. User registers an account.
2. Password is hashed using bcrypt before being stored.
3. User logs in with valid credentials.
4. JWT token is generated after successful authentication.
5. Token is stored and managed securely.
6. Authentication middleware verifies the user identity.
7. Authorization middleware checks the user role.
8. Access is granted or denied based on permissions.

---

## 📡 API Endpoints

### Authentication Routes

| Method | Endpoint | Description |
|---|---|---|
| POST | `/register` | Register a new user |
| POST | `/login` | Authenticate user and generate token |
| POST | `/logout` | Logout user |

### Protected Routes

| Method | Endpoint | Description |
|---|---|---|
| GET | `/profile` | Access user profile |
| GET | `/admin` | Access admin-only resources |

---

## 📁 Project Structure

```bash
User-Authentication-Authorization-System/
│
├── controllers/
│   └── authController.js
│
├── middleware/
│   └── authMiddleware.js
│
├── models/
│   └── User.js
│
├── routes/
│   └── authRoutes.js
│
├── .env
├── server.js
├── package.json
└── README.md
```

---

## 🔧 Installation

Clone the repository:

```bash
git clone https://github.com/MahiDoshi/User-Authentication-Authorization-System.git
```

Navigate to the project folder:

```bash
cd User-Authentication-Authorization-System
```

Install dependencies:

```bash
npm install
```

---

## 🔐 Environment Variables

Create a `.env` file in the root directory and add the following:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

---

## ▶️ Run the Application

Start the server:

```bash
npm start
```

For development mode:

```bash
npm run dev
```

---

## 🧪 Testing

Use **Postman** to test the authentication and authorization endpoints.

Recommended testing flow:

1. Register a new user.
2. Login with the registered credentials.
3. Access protected user routes.
4. Test admin-only routes with different user roles.
5. Verify that unauthorized users cannot access restricted resources.

---

## ✅ Project Outcome

This project successfully demonstrates the practical implementation of backend security concepts such as user registration, login authentication, password hashing, JWT token handling, protected routes, and role-based access control.

It provides a strong foundation for building secure REST APIs for modern web applications.

---

## 👩‍💻 Author

**Mahi Doshi**

---

## 📌 Repository

```text
User Authentication & Authorization System
```
