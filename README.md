# 📌 Pinterest Clone

A full-stack image sharing application inspired by Pinterest. Built with the MERN stack and enhanced with custom features such as image upload via ImageKit, JWT-based authentication, pin saving, user profile management, and board organization.

> ✅ This project is based on an open-source repository by [safak](https://github.com/safak/full-stack-pinterest), with significant modifications, UI refinements, and backend integrations contributed by [gunjans-git](https://github.com/gunjans-git).

---

## 🚀 Features

- 🔐 JWT Authentication (Sign up, Sign in)
- 🖼️ Image upload via [ImageKit](https://imagekit.io/)
- 📌 Create, save, and delete pins
- 📋 Organize pins into boards
- 👤 User profiles with saved & created pins
- 💬 Explore pins with infinite scroll
- 🎯 Mobile-responsive design
- 💾 MongoDB for persistent storage

---

## 🛠️ Tech Stack

### Frontend
- React
- Tailwind CSS
- React Router
- Axios

### Backend
- Node.js
- Express
- MongoDB (with Mongoose)
- ImageKit SDK
- JSON Web Token (JWT)

## 📦 Folder Structure

full-stack-pinterest/
├── client/ # React frontend
└── backend/ # Node.js backend

## ⚙️ How to Run the Project Locally

### Backend
cd backend
npm install
npm run dev

#Make sure to set up your .env with:
PORT=3000
MONGODB_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret

#Frontend
cd client
npm install
npm run dev

# Create a .env in /client with:
VITE_IMAGEKIT_PUBLIC_KEY=your_public_key
VITE_IMAGEKIT_URL_ENDPOINT=https://ik.imagekit.io/your_id/
VITE_IMAGEKIT_AUTH_ENDPOINT=http://localhost:3000/api/imagekit/auth
VITE_API_URL=http://localhost:3000

Acknowledgement
This project builds upon the structure and logic of the original Pinterest Clone by safak, modified and extended for learning and practical deployment.
