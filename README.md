
📚 Study App
A full-stack video course platform developed as part of coursework.
Includes separate user roles for Admin, Teacher, and Student with course upload and enrollment functionality.

🚀 Tech Stack
Backend: Node.js, Express, MongoDB (Mongoose)

Frontend: React + Vite

Database: MongoDB Atlas (Cloud)

Authentication: JWT

Styling: CSS

📂 Features
✅ User Registration & Login
✅ Admin Panel to manage courses
✅ Teachers can add courses with videos
✅ Students can enroll and view course content
✅ Role-based Dashboard Navigation

💻 Setup Instructions

Clone the repository

Backend Setup:


cd backend
npm install
Create a .env file with:
MONGO_DB = <your-mongo-link>
JWT_KEY = <your-secret>
PORT = 8000
node index.js

Frontend Setup:

Edit
cd frontend
npm install
npm run dev

🌐 Access
Frontend: http://localhost:5173

Backend API: http://localhost:8000

⚠️ Note
Sensitive details (MongoDB link, JWT secret) are kept in local .env files and excluded from GitHub using .gitignore.

