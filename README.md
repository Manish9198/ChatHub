# ChatHub – Real-Time Full-Stack Chat Application

ChatHub is a full-stack real-time chat application that enables secure one-to-one messaging with low latency. It is built using modern web technologies and demonstrates real-time communication, authentication, and scalable backend design.

---

## Features
- User authentication with JWT
- Real-time messaging using Socket.IO
- One-to-one private chats
- Secure password hashing
- MongoDB-based message storage
- Image/media upload support via Cloudinary
- Clean and responsive UI
- Scalable backend architecture

---

## Tech Stack

### Frontend
- React
- Vite
- JavaScript
- CSS

### Backend
- Node.js
- Express.js
- Socket.IO
- MongoDB (Mongoose)
- JWT Authentication

---

## Project Structure
```
chatApp/
│
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── middleware/
│   │   ├── models/
│   │   ├── routes/
│   │   └── index.js
│   ├── .env.example
│   ├── package.json
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── store/
│   │   └── App.jsx
│   ├── index.html
│   ├── package.json
│
├── .gitignore
└── README.md
```
---

## Prerequisites
Make sure you have the following installed:
- Node.js (v18 or above)
- npm
- MongoDB (local or Atlas)
- Git

---

## Environment Setup

Create a `.env` file inside the `backend` folder using the following format:
PORT=5001
MONGODB_URI=mongodb://localhost:27017/chathub
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
NODE_ENV=development

## Installation & Run (End-to-End)
### 1. Clone the Repository
```
git clone https://github.com/Manish9198/ChatHub.git
cd ChatHub
```
### 2. Install Backend Dependencies
```
cd backend
npm install
```
### 3. Install Frontend Dependencies
```
cd ../frontend
npm install
```
### 4. Start Backend Server
```
cd ../backend
npm run dev
```

Backend will run on: http://localhost:5001

### 5. Start Frontend Server
```
Open a new terminal:
cd frontend
npm run dev
```
Frontend will run on: http://localhost:5173


---

## How It Works
- User registers or logs in
- JWT is issued and stored securely
- Socket.IO establishes a real-time connection
- Messages are sent instantly and stored in MongoDB
- Only authenticated users can access chats

---

## Security Best Practices
- Passwords are hashed before storage
- JWT is used for route protection
- Environment variables are secured
- Sensitive keys are excluded from GitHub

---

## Future Improvements
- Group chats
- Read receipts
- Message search
- Push notifications
---

## Author
Manish Sutar

---

## License
This project is for learning and demonstration purposes.

