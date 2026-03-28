<div align="center">

# 📦 Order System Backend API

### A scalable, production-style backend for modern e-commerce and order-based platforms

Built with **Node.js**, **Express.js**, **MongoDB**, **Redis**, and modern backend best practices.

[![Node.js](https://img.shields.io/badge/Node.js-Backend-green?style=for-the-badge&logo=node.js)]()
[![Express.js](https://img.shields.io/badge/Express.js-API-black?style=for-the-badge&logo=express)]()
[![MongoDB](https://img.shields.io/badge/MongoDB-Database-green?style=for-the-badge&logo=mongodb)]()
[![Redis](https://img.shields.io/badge/Redis-Caching-red?style=for-the-badge&logo=redis)]()
[![JWT](https://img.shields.io/badge/JWT-Authentication-blue?style=for-the-badge&logo=jsonwebtokens)]()
[![Docker](https://img.shields.io/badge/Docker-Containerization-blue?style=for-the-badge&logo=docker)]()

</div>

---

## 🚀 Overview

**Order System Backend API** is a **production-oriented REST API** designed for **e-commerce and order management applications**.

It includes a complete backend workflow for:

- **Authentication & Authorization**
- **User / Admin role separation**
- **Product management**
- **Cart system**
- **Order lifecycle**
- **OTP-based verification**
- **Password recovery**
- **Security protections**
- **Redis-powered rate limiting**
- **Image handling**
- **Docker-based setup**

The project follows a **modular, scalable, and maintainable backend architecture**, making it suitable for:

- portfolio projects
- hackathons
- backend practice
- internship showcases
- real-world backend foundations

---

## 🔗 Repository

**GitHub:** [Devdeepakjha / OrderSystemProject](https://github.com/Devdeepakjha/OrderSystemProject)

---

# ✨ Features

## 🔐 Authentication & Security

- User Registration
- User Login
- JWT Access Token Authentication
- Refresh Token Flow
- Email OTP Verification
- Resend OTP
- Forgot Password
- Change Password
- Logout
- Role-Based Authorization (**User / Admin**)

---

## 👤 User Features

- View all products
- View product details
- Add products to cart
- Update cart quantity
- Remove products from cart
- Clear cart
- Place orders
- View personal orders

---

## 🛠️ Admin Features

- View all users
- View user details
- Delete users
- Add products
- Update products
- Delete products
- View all orders
- View single order
- Update order status

---

## 📦 Order & Cart System

- Dedicated cart management
- Quantity handling
- Cart cleanup
- Order placement flow
- Order history tracking
- Admin order control
- Order status updates

---

## 🛡️ Backend Protection

- JWT-protected routes
- Secure password hashing with **bcrypt**
- Request validation using **Zod**
- Centralized error handling
- Async wrapper handling
- Secure HTTP headers with **Helmet**
- NoSQL Injection protection
- XSS protection
- Rate limiting with **Redis**
- Standardized API response format

---

## ☁️ Media & Utility Support

- File upload handling using **Multer**
- Cloud image storage support via **Cloudinary**
- Email delivery support using **Nodemailer / Resend**
- Reusable utility functions
- Modular validation schemas

---

# 🧰 Tech Stack

## ⚙️ Core Backend

- **Node.js**
- **Express.js**

## 🗄️ Database

- **MongoDB**
- **Mongoose**

## 🔐 Auth & Security

- **JWT**
- **bcrypt**
- **helmet**
- **express-rate-limit**
- **express-mongo-sanitize**
- **xss-clean**

## ⚡ Performance & Infrastructure

- **Redis**
- **ioredis**
- **rate-limit-redis**
- **Docker**
- **Docker Compose**

## 📁 File / Media Handling

- **Multer**
- **Cloudinary**

## 📬 Email / Communication

- **Nodemailer**
- **Resend**

## ✅ Validation & API Tools

- **Zod**
- **Swagger JSDoc**
- **Swagger UI Express**

---

# 📁 Project Structure

```bash
OrderSystemProject/
│
├── .github/                  # Workflow / automation related files
├── config/                   # App, DB, Redis, Cloudinary, environment configs
├── Controllers/              # Route controllers / business logic
├── Middleware/               # Auth, error handling, validation, security middleware
├── Models/                   # Mongoose schemas
├── Routes/                   # API route definitions
├── utils/                    # Helper functions / reusable utilities
├── ValidationSchema/         # Zod validation schemas
│
├── .dockerignore
├── .gitignore
├── docker-compose.yml
├── Dockerfile
├── package.json
├── package-lock.json
├── README.md
├── server.js                 # Application entry point
```
