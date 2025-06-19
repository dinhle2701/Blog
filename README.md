<h1 align="center">📝 Blog App</h1>

Welcome to my personal blog project — a space where I share insights, experiences, and thoughts about programming, technology, life, and career journeys.

## 🚀 Demo
You can check out the live version here: 

## 🧠 Features

### 🛡️ Admin Features

### 👤 User Features
- Login / Register accounts


## 🛠️ Tech Stack

| Layer      | Technology                          |
|------------|-------------------------------------|
| Frontend   | Next.JS + Tailwind CSS              |
| Backend    | Spring Boot + Spring Security       |
| Database   | MongoDB (Mongoose ODM)              |
| Auth       | JWT + Role-based Auth               |
| State Mgmt | Redux Toolkit + RTK Query           |
| Deployment | Amazon EC2 (backend)                |          
|            | Amazon CloudFront + S3 (frontend)   |
|            | Amazon DynamoDB                     |

## 📦 Project Structure
```
Blog/
├── blog_backend/
│ ├── src/
| | ├── main/
| | | ├── java
| | | | ├── com.project.blog_backend
| | | | ├── config/
| | | | ├── controller/
| | | | ├── dto/
| | | | | ├── req/
| | | | | └── res/
| | | | ├── models/
| | | | ├── repository/
| | | | ├── service/
| | | | | └── serviceImpl/
| | | | └── BlogBackendApplication.java
| | | └── resource/
| | └── test/
│ ├── target/
│ └── pom.xml
├── blog_frontend/
| │ ├── .next/
| │ ├── node_modules/
| │ ├── public/
| │ ├── src/
| │ ├── package.json
| │ └── package-lock.json
```

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/dinhle2701/Blog
cd blog
```

### 2. Start Project

#### 2.1 Backend
```
local: right click to Ecommerce_backend folder and click "Open Folder as Intellij IDEA Project"
link: http://localhost:5656
```

#### 2.2 Frontend
```
cd frontend -> npm install -> npm run dev
link: http://localhost:3000
```