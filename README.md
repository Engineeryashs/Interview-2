🚀 User-Specific Todo App

A full-stack MERN application where users can securely manage their own todos with authentication and protected routes.

✨ Features
🔐 JWT Authentication (Login / Signup)
👤 User-specific todos (data isolation)
✅ Create, Read, Update, Delete todos
🛡️ Protected routes with middleware
📦 Input validation using Zod


🛠️ Tech Stack
Frontend: React.js
Backend: Node.js, Express.js
Database: MongoDB
Auth: JWT, bcrypt


⚙️ How It Works
User → Login/Signup → Get Token
     → Send Token in Headers
     → Access Protected APIs
     → Manage Own Todos

     
📡 API Endpoints
Method	Endpoint	Description
POST	/signup	Register user
POST	/login	Login user
GET	/todos	Get user todos
POST	/todos	Create todo
PUT	/todos/:id	Update todo
DELETE	/todos/:id	Delete todo


🔑 Key Concept

Each todo is linked with userId → ensures only owner can access their data

🧠 Learnings
Authentication & Authorization
REST API design
Middleware usage
Full-stack integration
