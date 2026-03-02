# 💼 Indeed Clone

A full-stack **Indeed Job Portal Clone** built using **Spring Boot**, **React**, **Material UI**, **MongoDB Compass**, and **Hibernate**.

This project allows users to search and explore job listings similar to the Indeed platform.

---

## 🚀 Features

- Search Jobs by Title  
- View Company Details  
- View Job Descriptions  
- Browse Job Listings  
- Responsive UI using Material UI  
- Full-stack integration (React + Spring Boot)  
- MongoDB Database Integration  

No authentication system included (open job browsing system)

---

## 🧠 Tech Stack

### Frontend:
- React (Vite)
- Material UI
- Axios

### Backend:
- Spring Boot
- Spring Data
- Hibernate

### Database:
- MongoDB Compass

---

## ⚙️ Project Architecture

React UI → Spring Boot REST API → Hibernate → MongoDB

---

## 📸 Screenshots

### 🖥 Frontend UI
![Frontend](screenshots/frontend.png)

### 🗄 Backend (MongoDB Data)
![Backend](screenshots/backend.png)

---

## 📂 Folder Structure

indeed-clone/

backend/            # Spring Boot Application  
frontend/           # React Application  
screenshots/        # Project Images  
README.md  

---

## 🔌 API Functionality

The backend provides APIs to:

- Fetch job listings  
- Search jobs  
- View job details  

---

## 🧪 Tested Using

- Browser UI  
- MongoDB Compass  

---

## 🛠 Setup Instructions

### Backend:

cd backend  
mvn spring-boot:run  

### Frontend:

cd frontend  
npm install  
npm run dev  

### Database Setup:

1. Open MongoDB Compass  
2. Create database (example: indeedDB)  
3. Add this in application.properties:

spring.data.mongodb.uri=mongodb://localhost:27017/indeedDB

---

## 🖥 Application Flow

User → React UI → Spring Boot API → MongoDB → Job Data Displayed

---

## 📌 Future Improvements

- Authentication  
- Job Apply Feature  
- Admin Panel  
- Saved Jobs  

---

## 👩‍💻 Author

Priyanshi Kumari  
MCA Student | Full Stack Developer  
GitHub: Priyanshi731
