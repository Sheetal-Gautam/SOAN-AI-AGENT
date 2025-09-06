# Soan AI Agent

A full-stack AI-powered project management application built with the MERN stack (MongoDB, Express, React, Node.js) and enhanced with AI features.

---

## Features

- User authentication and authorization (JWT)
- AI-powered project management tools
- RESTful API with modular controllers and services
- Real-time communication via sockets
- Redis caching for performance optimization
- Responsive frontend with React, Vite, and Tailwind CSS

---

## Folder Structure

```
soen/
  backend/    # Node.js, Express, MongoDB, Redis
  frontend/   # React, Vite, Tailwind CSS
```

---

## Getting Started

### Prerequisites

- Node.js (v16+)
- npm
- MongoDB (running locally or cloud)
- Redis (if enabled in services)

---

### 1. Clone the Repository

```bash
git clone <[your-repo-url](https://github.com/Sheetal-Gautam/SOAN-AI-AGENT/>
cd soen
```

---

### 2. Backend Setup

```bash
cd backend
npm install
# Configure your .env file with MongoDB URI, JWT secret, etc.
npm start
```

---

### 3. Frontend Setup

```bash
cd ../frontend
npm install
npm run dev
```

---

### 4. Access the Application

- Backend API: `http://localhost:5000` (default)
- Frontend: `http://localhost:5173` (default)

---

## Environment Variables

Create a `.env` file in the `backend/` directory with the following (example):

```
MONGODB_URI=mongodb://localhost:27017/soan-ai-agent
JWT_SECRET=your_jwt_secret
REDIS_URL=redis://localhost:6379
PORT=5000
```

---

## Scripts

**Backend:**
- `npm start` — Start the backend server

**Frontend:**
- `npm run dev` — Start the frontend development server

---

## License

This project is for educational
