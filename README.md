# Task Manager App

A complete backend API for managing tasks with full CRUD operations and user authentication.  
Built using **Node.js + Express** with JWT authentication, middleware, and clean folder structure.

`

## 🛠 Tech Stack
- Node.js  
- Express.js  
- MongoDB / MySQL (choose one you used)  
- JWT Authentication  
- Middleware (auth, error handling)  
- Postman for testing  

## 📂 Project Structure
```
src/
 ├── controllers/
 ├── routes/
 ├── middleware/
 ├── models/
 ├── config/
 └── index.js
```
## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Riteshconnect/taskManagerApp.git
cd taskManagerApp
```

### 2️⃣ Install Dependencies
```bash
npm install
```


## 📡 API Endpoints

### 🔹 Auth
```
POST /api/auth/register
POST /api/auth/login
```

### 🔹 Tasks
```
GET    /api/tasks        → Get All Tasks
POST   /api/tasks        → Create Task
GET    /api/tasks/:id    → Get Task by ID
PUT    /api/tasks/:id    → Update Task
DELETE /api/tasks/:id    → Delete Task
```

---

## 🧪 Sample Responses

### Task object:
```json
{
  "id": "67a12c9d3fa8",
  "title": "Complete project",
  "description": "Finish API routes",
  "completed": false,
  "createdAt": "2025-11-22T08:30:00Z"
```
---
## 📝 Future Improvements
- Add priorities (low/medium/high)  
- Add task categories  
- Add user dashboard or admin panel  

## 👨‍💻 Author
**Ritesh Kumar**  
Node.js Backend Developer  
LinkedIn:www.linkedin.com/in/ritesh-kumar-992334232 
GitHub: https://github.com/Riteshconnect

