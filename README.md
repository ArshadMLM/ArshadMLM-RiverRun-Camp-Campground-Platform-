# 🏕️ RiverRun Camp – Campground Discovery Platform

**RiverRun Camp** is a full-stack web application that allows users to explore, review, and manage campground listings. The platform combines interactive maps, user-generated content, and secure authentication to deliver a complete campground discovery experience.

---

# 🌍 Overview

RiverRun Camp is designed to simplify the process of finding and sharing camping destinations. Users can browse campgrounds, view detailed information, upload images, and leave reviews, creating a community-driven platform for outdoor enthusiasts.

---

# 🎯 Objectives

## Primary Goal

Build a secure and scalable web application that:

* Enables users to discover campgrounds easily
* Supports user-generated content (reviews, listings)
* Provides interactive location-based exploration
* Ensures safe and validated user interactions

## Target Users

### 🏕️ Travelers & Campers

* Discover new camping locations
* View ratings and reviews
* Explore locations on a map

### ✍️ Contributors

* Add new campgrounds
* Upload images
* Share personal experiences through reviews

---

# ✨ Key Features

## 🔐 Authentication & Authorization

* Secure user registration and login
* Session-based authentication using Passport.js

## 🏕️ Campground Management

* Create, edit, and delete campground listings
* View detailed campground information

## ⭐ Review System

* Add and remove reviews
* Rate campgrounds based on user experience

## 🗺️ Interactive Map Integration

* Mapbox-powered cluster maps
* Visual exploration of campground locations

## 📸 Image Handling

* Cloudinary integration for image upload and storage

## 🔒 Security Enhancements

* Input validation with Joi
* Data sanitization to prevent injection attacks
* Centralized error handling

## 📱 Responsive UI

* Mobile-friendly design using Tailwind CSS

---

# 🛠️ Technology Stack

## Backend

* Node.js
* Express.js
* MongoDB
* Mongoose

## Frontend

* EJS templating
* Tailwind CSS
* PostCSS

## Integrations & Services

* Mapbox (maps and geolocation)
* Cloudinary (image hosting)
* Passport.js (authentication)
* Express Session (session management)

---

# 🏗️ Application Structure

```
RiverRun-Camp/
├── controllers/        # Business logic handlers
├── models/             # Database schemas
├── routes/             # Route definitions
├── views/              # EJS templates
├── public/             # Static assets (CSS, JS)
├── cloudinary/         # Image configuration
├── utils/              # Helper utilities
├── seeds/              # Sample data scripts
└── app.js              # Main server entry point
```

---

# 🔄 Core Workflows

## User Authentication

1. User registers or logs in
2. Credentials are validated
3. Session is created for authenticated access

## Campground Browsing

1. User visits campground listings
2. Data is fetched from MongoDB
3. Results are displayed with map integration

## Review Submission

1. User selects a campground
2. Submits rating and feedback
3. Review is stored and displayed

---

# 🚀 Setup Instructions

## 1. Clone Repository

```bash
git clone https://github.com/UmairStn/RiverRun-Camp.git
cd RiverRun-Camp
```

## 2. Install Dependencies

```bash
npm install
```

## 3. Configure Environment Variables

Create a `.env` file and include:

```env
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_KEY=your_key
CLOUDINARY_SECRET=your_secret
MAPBOX_TOKEN=your_token
DB_URL=your_mongodb_uri
SECRET=your_session_secret
```

## 4. Seed Database (Optional)

```bash
node seeds/index.js
```

## 5. Run Application

```bash
npm start
```

Access the app at:
`http://localhost:3000`

---

# 🔐 Security Measures

* Joi-based request validation
* MongoDB query sanitization
* Authentication middleware
* Centralized error handling
* Async error management utilities

---

# 📌 Project Highlights

* Full-stack CRUD application
* Map-based data visualization
* Secure authentication system
* Cloud-based media management
* Clean MVC architecture

---

# 🔮 Future Improvements

* User profiles and saved campgrounds
* Advanced search and filtering
* Booking/reservation system
* Real-time notifications
* API-based mobile app support

---

# 👨‍💻 Contributor

**ArshadMLM**
GitHub: [https://github.com/ArshadMLM](https://github.com/ArshadMLM)

---

# ⭐ Final Note

RiverRun Camp highlights the integration of mapping services, secure backend systems, and user-driven content in a modern web application. It demonstrates strong capabilities in full-stack development, RESTful architecture, and real-world application desi
