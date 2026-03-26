# Smart Gym - Full-Stack Fitness Management System

This project implements a centralized management platform for gym operations. It features a React frontend and a Node.js backend to handle member registrations, trainer scheduling, and real-time class reservations through a unified digital dashboard.

Modern Full-Stack Club Management in JavaScript

## Overview
This project demonstrates how a full-stack architecture can be applied to streamline business operations in the fitness industry. It uses an Express-based REST API to manage a MongoDB database, allowing gym owners to track member status, manage trainer availability, and process facility reservations seamlessly.

The system includes a modern web interface built with Vite and React, providing a responsive experience for managing staff and athlete data.

## Features
- **Full-Stack MERN Architecture:** Integrates React, Node.js, Express, and MongoDB
- **Member Management System:** Handles CRUD operations for gym member profiles
- **Automated Reservation Logic:** Manages class bookings and facility scheduling
- **Trainer Performance Tracking:** Dedicated modules for staff and trainer administration
- **Responsive Web Dashboard:** Modern UI built with Vite for high-speed performance
- **Scalable REST API:** Asynchronous backend endpoints for high-concurrency requests

## How It Works
- The frontend client sends HTTP requests to the Node.js server using standard REST methods
- The backend server processes incoming data and enforces business logic for gym policies
- MongoDB serves as the persistent storage layer for all member and reservation records
- React Router DOM manages navigation between Home, Members, and Trainers views
- Secure environment variables handle database connections and sensitive API keys
- The frontend updates dynamically to reflect changes in member counts or booking status
- Middleware handles JSON parsing and Cross-Origin Resource Sharing (CORS) for security

## Prerequisites
- Node.js (v14 or higher)
- MongoDB (Local or Atlas Cloud)
- Required libraries: express, mongoose, cors, react-router-dom, vite
