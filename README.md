# Task Manager App ✅

<div align="center">

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=json-web-tokens&logoColor=white)

**Full-stack task management application**

</div>

---

## ✨ Features

- 🔐 **User Authentication** — Register, Login with JWT
- ✅ **Create Tasks** — Add tasks with title, description, due date
- 📝 **Update Tasks** — Edit task details anytime
- 🗑️ **Delete Tasks** — Remove completed or unwanted tasks
- 🔄 **Status Tracking** — Pending → In Progress → Done
- 🔍 **Filter & Search** — Filter tasks by status or search by name
- 📱 **Responsive UI** — Works on mobile and desktop
- ⚡ **Real-time Updates** — Instant UI feedback on all actions

---

## 🛠️ Tech Stack

### Frontend
- **React** — UI framework
- **React Router** — Navigation
- **Axios** — API calls
- **CSS3** — Styling

### Backend
- **Node.js** + **Express** — REST API
- **SQL** (MySQL/PostgreSQL) — Database
- **JWT** — Authentication tokens
- **bcrypt** — Password hashing

---

## ⚡ Quick Start

### Backend
```bash
cd backend
npm install

# Configure your database in .env
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=yourpassword
DB_NAME=taskmanager
JWT_SECRET=your_secret_key

npm start
```

### Frontend
```bash
cd frontend
npm install
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📁 Project Structure

```
task-manager-app/
├── backend/
│   ├── controllers/    # Task & Auth controllers
│   ├── middleware/     # JWT auth middleware
│   ├── models/         # Task & User models
│   ├── routes/         # API routes
│   └── server.js
└── frontend/
    ├── src/
    │   ├── components/ # TaskCard, TaskForm, Navbar
    │   ├── pages/      # Login, Register, Dashboard
    │   └── App.js
    └── package.json
```

---

## 🔑 API Endpoints

| Method | Endpoint | Auth | Description |
|---|---|---|---|
| POST | /api/auth/register | Public | Register user |
| POST | /api/auth/login | Public | Login user |
| GET | /api/tasks | User | Get all tasks |
| POST | /api/tasks | User | Create task |
| PUT | /api/tasks/:id | User | Update task |
| DELETE | /api/tasks/:id | User | Delete task |

---

## 👤 Author

**Pavan R Yadav**
- GitHub: [@PAVANRYADUVANSHI](https://github.com/PAVANRYADUVANSHI)
- Email: pavanryavdavkumsi25@gmail.com
