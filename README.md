# Task Management System

A full-stack **Task Management System** built as part of a software development internship program. This application supports creating, editing, deleting, and tracking tasks with advanced features such as collaboration, analytics, real-time notifications, dark mode, and file attachments.

---

## 📂 Project Structure

```
root/
├── client/        # React frontend (Tailwind CSS, Axios)
├── server/        # Node.js backend (Express.js, MongoDB)
└── README.md
```

---

## 🚀 Features

### ✅ Week 1: Backend Development

* Express.js server setup
* MongoDB integration using Mongoose
* REST API endpoints:

  * `POST /tasks` - Create a task
  * `GET /tasks` - Retrieve all tasks
  * `GET /tasks/:id` - Get task by ID
  * `PUT /tasks/:id` - Update task
  * `DELETE /tasks/:id` - Delete task
* Data validation and error handling

### 🧩 Week 2: Frontend Development

* Built using React.js
* Components:

  * `TaskForm` - Add/Edit task
  * `TaskList` - List all tasks with filters
  * `TaskDetails` - View detailed info
* API communication using Axios
* Styled with Tailwind CSS
* Fully responsive UI

### 🔐 Week 3: Advanced Features

* Authentication (JWT-based):

  * `POST /auth/register`
  * `POST /auth/login`
* Protected routes using middleware
* Filters by status (Pending, In Progress, Completed)
* Search tasks by title or description
* UI refinements

### 🤝 Week 4: Collaboration + Notifications

* Share tasks with other users

  * `PUT /tasks/:id/share`
  * `GET /tasks/shared`
* Real-time notifications with Socket.IO:

  * Task shared with you
  * Task status updated
* Notifications shown in real-time in UI

### 📊 Week 5: Analytics Dashboard

* Analytics backend:

  * `GET /analytics/overview`
  * `GET /analytics/trends`
* Dashboard component:

  * Total tasks, completed, pending
  * Weekly trend chart (bar/line)
  * Status breakdown (pie chart)
* Chart.js or Recharts used for visualization

### 🌐 Week 6: Final Enhancements & Deployment

* Dark mode toggle support
* Task attachments (images/files)
* Deployment:

  * Frontend: Vercel/Netlify
  * Backend: Render/Railway
* Comprehensive testing & polish

---

## ⚙️ Tech Stack

| Frontend | Backend | Database | Other                                                   |
| -------- | ------- | -------- | ------------------------------------------------------- |
| React.js | Node.js | MongoDB  | Tailwind CSS, Socket.IO, JWT, Multer, Chart.js/Recharts |

---

## 📥 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/task-management-system.git
cd task-management-system
```

### 2. Backend Setup

```bash
cd server
npm install

# Set environment variables
cp .env.example .env
# Fill in MONGO_URI and JWT_SECRET in the .env file

npm run dev
```

### 3. Frontend Setup

```bash
cd client
npm install
npm start
```

---

## 🔐 API Documentation

### Authentication

| Method | Endpoint           | Description         |
| ------ | ------------------ | ------------------- |
| POST   | /api/auth/register | Register a new user |
| POST   | /api/auth/login    | Login and get token |

### Task Routes

| Method | Endpoint              | Description            |
| ------ | --------------------- | ---------------------- |
| GET    | /api/tasks            | Get all tasks          |
| GET    | /api/tasks/\:id       | Get a single task      |
| POST   | /api/tasks            | Create new task        |
| PUT    | /api/tasks/\:id       | Update task            |
| DELETE | /api/tasks/\:id       | Delete task            |
| PUT    | /api/tasks/\:id/share | Share task with a user |
| GET    | /api/tasks/shared     | Get shared tasks       |

### Analytics

| Method | Endpoint                | Description   |
| ------ | ----------------------- | ------------- |
| GET    | /api/analytics/overview | Status count  |
| GET    | /api/analytics/trends   | Weekly trends |


---

## 🙋‍♂️ Author

Sehrish Noor
BS Software Engineering | GIKI

> ✨ Built with hard work, learning, and creativity!
