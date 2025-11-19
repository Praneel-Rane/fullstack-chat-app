# 💬 Full-Stack Chat Application

A real-time chat application with secure authentication, user profiles, and instant messaging powered by Socket.IO.

🔗 **Live Demo**: https://fullstack-chat-app-culf.onrender.com/

## 🚀 Features

- 🔐 Secure user authentication (JWT + bcrypt)
- 💬 Real-time messaging using Socket.IO
- 🟢 Online user status indicator
- 🖼 Cloudinary profile image upload
- ⚡ Fast response and clean UI
- 📱 Fully responsive design

## ✨ Highlights

- 🌟 Tech stack: MERN + Socket.io + TailwindCSS + DaisyUI
- 🎃 Authentication & Authorization with JWT
- 👾 Real-time messaging with Socket.io (WebSockets)
- 🚀 Online user status tracking
- 👌 Global state management (Zustand)
- ☁️ Deployed on Render

## 🔑 Setup `.env` file (Backend)

Create a `.env` file in the backend folder and add:

```env
MONGODB_URI=your_mongo_uri_here
JWT_SECRET=your_jwt_secret_here
CLOUDINARY_CLOUD_NAME=your_cloudinary_name_here
CLOUDINARY_API_KEY=your_cloudinary_key_here
CLOUDINARY_API_SECRET=your_cloudinary_secret_here
PORT=5000
NODE_ENV=development

## 🔧 Setup and Run Locally (Optional)

> Requires your own MongoDB + Cloudinary credentials in `.env` file.

```bash
# Clone the project

# Enter project folder and install dependencies for frontend
cd frontend
npm install
npm run dev 

# Open new terminal and start backend
cd ../backend
npm install
npm run dev 

