# Node.js Security & Authentication Masterclass

This repository contains robust implementations of backend security features using Node.js, Express, and MongoDB. It focuses on protecting user data and managing secure sessions.

## 🚀 Key Features
- *Secure Authentication:* Implementation of JWT (JSON Web Tokens) for stateless authentication.
- *Password Hashing:* Utilizing *Bcrypt* with a salt round of 10 to securely hash passwords before database storage.
- *Session Management:* Using *Cookies* with httpOnly and secure flags to prevent XSS and CSRF attacks.
- *Stateful Sessions:* Implementation of server-side sessions for sensitive data handling.

## 🛠️ Tech Stack
- *Runtime:* Node.js
- *Framework:* Express.js
- *Database:* MongoDB (Mongoose ODM)
- *Security Libraries:* Bcrypt, JSONWebToken, Cookie-parser
