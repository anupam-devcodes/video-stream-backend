# VideoStream Backend API

A scalable backend application built with Node.js, Express.js, MongoDB, and JWT authentication. The project simulates the backend architecture of a video-sharing platform and implements industry-standard authentication, user management, media handling, and engagement features.

---

## Features

### Authentication & Security
- JWT-based Authentication
- Access Token & Refresh Token Flow
- Password Hashing using bcrypt
- Protected Routes & Authorization

### User Management
- User Registration & Login
- Profile Management
- Avatar & Cover Image Uploads
- Account Updates

### Video Management
- Upload Videos
- Update Video Details
- Delete Videos
- Publish / Unpublish Videos

### Social Features
- Like / Unlike Videos
- Comment System
- Reply Support
- Subscribe / Unsubscribe Channels

### Media Handling
- Cloudinary Integration
- Image Upload Management
- Video Asset Management

---

## Tech Stack

### Backend
- Node.js
- Express.js

### Database
- MongoDB
- Mongoose

### Authentication
- JWT
- bcrypt

### Media Storage
- Cloudinary

### Tools
- Postman
- Git
- GitHub

---

## API Architecture

The application follows a modular backend architecture:

```text
src/
├── controllers/
├── models/
├── routes/
├── middlewares/
├── utils/
├── services/
└── database/
```

---

## Key Learnings

- REST API Design
- Authentication & Authorization
- Token Management
- MongoDB Data Modeling
- Backend Scalability Practices
- File Upload Handling
- Production-Ready Project Structure

---

## Installation

```bash
git clone <repository-url>

cd video-stream-backend

npm install

npm run dev
```

---

## Environment Variables

```env
PORT=
MONGODB_URI=

ACCESS_TOKEN_SECRET=
ACCESS_TOKEN_EXPIRY=

REFRESH_TOKEN_SECRET=
REFRESH_TOKEN_EXPIRY=

CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
```

---

## Future Improvements

- Video Streaming Optimization
- Notifications System
- Watch History
- Recommendation Engine
- Analytics Dashboard

---

## Author

Anupam Choubey
