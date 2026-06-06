# User Authentication & Authorization System
A secure backend-focused web application built with Node.js, Express.js, and MongoDB that
provides user authentication, authorization, and role-based access control (RBAC). The project
implements industry-standard security practices such as JWT authentication, password
hashing, secure cookie management, and protected routes.
**Features**
• User Registration and Login
• JWT-Based Authentication
• Password Hashing with bcrypt
• Role-Based Access Control (Admin/User)
• Protected Routes and Middleware
• Secure Cookie Management
• Environment Variable Configuration
• RESTful API Architecture
• Postman API Testing
• Simple Frontend Interface for Demonstration
**Technology Stack:**
Backend
• Node.js
• Express.js
• MongoDB
• Mongoose
**Security**
• JSON Web Token (JWT)
• bcrypt
• cookie-parser
• dotenv
**Tools**
• Postman
• Git & GitHub
Frontend
• HTML
• CSS
• JavaScript
**Workflow**
1. User registers an account.
2. Password is hashed using bcrypt before storage.
3. User logs in with valid credentials.
4. JWT token is generated upon successful authentication.
5. Token is stored and managed using cookies.
6. Authentication middleware verifies user identity.
7. Authorization middleware checks user roles.
8. Access is granted or denied based on permissions.
9. APIs are tested using Postman and demonstrated through a simple frontend interface.
**API Endpoints:**
**Authentication**
• POST /register – Register a new user
• POST /login – Authenticate user and generate token
• POST /logout – Logout user
**User**
• GET /profile – Access user profile
**Admin**
• GET /admin – Access admin-only resources
Installation
git clone <repository-url>
cd project-folder
npm install
**Environment Variables**
Create a .env file in the root directory and add:
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
Run the Application
npm start
For development:
npm run dev
Testing
Use Postman to test all authentication and authorization endpoints. Verify role-based access
control by creating users with different roles and accessing protected routes.
**Project Outcome**
Successfully developed a secure authentication and authorization system capable of handling
user registration, login, authentication, and role-based access control. The project demonstrates
practical implementation of backend security concepts and scalable REST API development
for modern web applications.
