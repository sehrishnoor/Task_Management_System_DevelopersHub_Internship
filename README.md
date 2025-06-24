# 📝 Task Management System

A full-stack task management application built using **Node.js**, **Express.js**, **MongoDB**, and **React.js**. Designed for software development interns to learn complete project lifecycle development including backend APIs, frontend interface, user authentication, and responsive design.

---

## 📌 Features

### ✅ Backend
- RESTful API with CRUD operations for tasks
- MongoDB with Mongoose ODM
- User Authentication using JWT
- Request validation with middleware
- Centralized error handling

### 🎨 Frontend
- Task listing with filtering and search
- Task creation and editing form
- Task details view
- Responsive design with Tailwind CSS
- API communication with Axios

---

## 🔧 Tech Stack

| Layer     | Technology             |
|-----------|------------------------|
| Backend   | Node.js, Express.js    |
| Database  | MongoDB, Mongoose      |
| Frontend  | React.js, Tailwind CSS |
| Auth      | JWT, bcryptjs          |
| Utils     | dotenv, cors, axios    |

---

## 🗂 Folder Structure

### Backend
/backend
├── controllers/
├── models/
├── routes/
├── middleware/
├── config/
├── app.js or server.js
### Frontend
/frontend
├── components/
├── services/
├── pages/
├── styles/
├── App.js

---

## 🚀 Getting Started

### ✅ Prerequisites
- Node.js & npm
- MongoDB (local or cloud e.g. MongoDB Atlas)

---

## 🔙 Backend Setup

```bash
# Clone the repo
git clone https://github.com/your-username/task-management-system.git
cd backend

# Install dependencies
npm install

# Create .env file
touch .env

Add this to .env:
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
# Run the server
npm run dev
Server runs on http://localhost:5000

# Navigate to frontend
cd ../frontend

# Install dependencies
npm install

# Create .env file
touch .env
Add this to .env:

REACT_APP_API_URL=http://localhost:5000/api

# Start React app
npm start
🧭 Usage Guide
+ Add Task – Create a new task

View all tasks with title, status, and due date

Click a task to see full details

Edit or delete existing tasks

Use search & filter to find tasks

(Optional) Register/Login to manage tasks securely

🔐 Optional Advanced Features
🔐 User Authentication

🔎 Search by title/description

✅ Filter by status: Pending, In Progress, Completed

📊 Task completion progress bar

🧪 Testing
Backend (with Jest or Mocha):

npm test
Frontend (with React Testing Library)

```bash

👩‍💻 Author
Sehrish Noor
BS Software Engineering (2nd Year)
Ghulam Ishaq Khan Institute (GIKI)
Languages: C++, JavaScript, Python

---
