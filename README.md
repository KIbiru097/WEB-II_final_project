# 🎓 Lost & Found Management System

A comprehensive web application for managing lost and found items at a university campus. This system connects students who lose items with those who find them through a secure, searchable platform with verification workflows.

## 📋 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Project Structure](#project-structure)
- [Installation Guide](#installation-guide)
- [Environment Variables](#environment-variables)
- [Database Setup](#database-setup)
- [API Documentation](#api-documentation)
- [Running the Application](#running-the-application)
- [User Roles](#user-roles)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

## 🎯 Overview

The Lost & Found Management System is a capstone-level project built for university students to:

- **Report** lost and found items with detailed information and photos
- **Search** for items using various filters (name, category, location, date)
- **Claim** ownership of found items with verification evidence
- **Track** claim status throughout the process
- **Manage** all reports and claims through an admin dashboard
- **View** statistics and analytics on lost/found trends

### Problem Solved
Students frequently lose valuable items on campus with no efficient way to recover them. This system eliminates the need for physical bulletin boards and creates a centralized digital platform for item recovery.

## ✨ Features

### 👤 Student Features
- User registration and authentication
- Profile management with password change
- Report lost items with photos
- Report found items with photos
- Search and filter items by:
  - Item name
  - Category
  - Location
  - Date range
  - Status
- View personal reports (lost & found)
- Submit ownership claims with verification details
- Track claim status (Pending/Approved/Rejected)
- Edit and delete own reports

### 👑 Admin Features
- Admin dashboard with statistics
- Manage all users
- View and manage lost reports
- View and manage found reports
- Review ownership claims
- Approve or reject claims
- Mark items as returned
- Delete fake reports
- View system analytics
- Activity monitoring

### 🔐 Security Features
- JWT-based authentication
- Bcrypt password hashing
- Role-based access control (RBAC)
- Protected API routes
- Input validation and sanitization
- File upload restrictions
- Request logging
- Environment variables for sensitive data

## 🛠️ Technology Stack

### Backend
- **Node.js** - JavaScript runtime
- **Express.js** - Web framework
- **PostgreSQL** - Relational database
- **JWT** - Authentication tokens
- **Bcryptjs** - Password hashing
- **Multer** - File upload handling
- **Winston** - Logging
- **Helmet** - Security headers
- **CORS** - Cross-origin resource sharing

### Frontend (Optional - React)
- **React.js** - UI framework
- **React Router** - Navigation
- **Axios** - HTTP client
- **Bootstrap/Tailwind** - Styling (optional)

### Development Tools
- **Nodemon** - Auto-restart during development
- **dotenv** - Environment variables
- **Morgan** - HTTP request logging

## 📂 Project Structure
