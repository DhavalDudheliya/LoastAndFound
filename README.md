# Lost and Found Helper System for University 🚀

**Project Duration 🗓️**: January 2023 – March 2023

**Project Description 📃**: A platform designed to help students retrieve lost items efficiently, using Google authentication and email notifications. This system streamlines the process of managing lost and found items, significantly reducing the need for physical office visits.

---

## Table of Contents 📋
1. [About the Project](#about-the-project)
2. [Tech Stack](#tech-stack)
3. [Features](#features)
4. [Installation](#installation)
5. [Contact](#contact)

---
  
## About the Project ⓘ

### Overview
he Lost and Found Helper System is a university platform that allows students to retrieve lost items with ease. Through Google authentication and email notifications, the system reduces the need for students to visit the office physically. It also features an admin and coordinator portal for efficient management of users and items, including CSV report generation.

## Tech Stack 🚀📋

- **Frontend**: React, MUI
- **Backend**: Node.js, Express.js
- **Database**: MongoDB, Mongoose
- **Authentication**: passport-google-oauth2.0
- **Email Notifications**: Nodemailer
- **Version Control**: Git, GitHub

---

## Features 📱🖥️

- **Google Authentication**: Provides secure login for students using their university Google accounts.
- **Item Status Management**: Tracks the status of lost items, reducing the need for physical office visits.
- **Admin & Coordinator Portal**: Manages users and items, including the ability to generate CSV reports.
- **Email Notifications**: Sends email updates to students about the status of their lost items.
- **Report Generation**: Allows admins to generate CSV reports for better tracking and management.

---

## Installation

### Prerequisites
- Node.js (version)
- MongoDB (local or cloud setup)
- npm or yarn

### Setup ⚙️

1. **Clone the repository**:
   ```bash
   git clone https://github.com/DhavalDudheliya/Hostel_Management.git
   cd Hostel_Management

2. **Install dependencies**:
   ```bash
   # Install server dependencies
   cd backend
   npm install

   # Install client dependencies
   cd ../frontend
   npm install

3. Set up environment variables: 
   # Backend
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   RAZORPAY_KEY=your_razorpay_key
   RAZORPAY_SECRET=your_razorpay_secret

   # Frontend
   REACT_APP_API_URL=your_backend_api_url

4. Run the project:
   ```bash
   # Run the backend
   cd backend
   npm run server

   # Run the frontend
   cd ../frontend
   npm run start

---

## Contact 📩📞

- Email: dhavaldudheliya77@gmail.com
- Phone No: +91 9157795624

