# Eventify - Event Management System

This project is split into two main parts: frontend and backend.

## Project Structure

```
eventify/
├── frontend/           # React + Vite frontend application
│   ├── src/           # Source files
│   ├── public/        # Static files
│   └── package.json   # Frontend dependencies
│
└── backend/           # Express + MongoDB backend
    ├── src/
    │   ├── controllers/  # Route controllers
    │   ├── models/       # MongoDB models
    │   ├── routes/       # API routes
    │   ├── config/       # Configuration files
    │   ├── middleware/   # Custom middleware
    │   └── index.js      # Main application file
    └── package.json      # Backend dependencies
```

## Setup Instructions

### Backend Setup

1. Navigate to the backend directory:
   ```bash
   cd backend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the backend directory with the following variables:
   ```
   PORT=5000
   MONGODB_URI=your_mongodb_atlas_connection_string_here
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

## Development

- Backend runs on: http://localhost:5000
- Frontend runs on: http://localhost:5173

## MongoDB Atlas Setup

1. Create a MongoDB Atlas account at https://www.mongodb.com/cloud/atlas
2. Create a new cluster
3. Get your connection string from the Atlas dashboard
4. Add the connection string to your backend `.env` file

## Technologies Used

### Frontend
- React
- TypeScript
- Vite
- Tailwind CSS
- Shadcn UI Components

### Backend
- Node.js
- Express
- MongoDB Atlas
- Mongoose 