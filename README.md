# 📌 Recruitment Portal Project

A full-stack Recruitment Management System built using **React** (frontend) and **Spring Boot** (backend).  
This project streamlines the hiring process by allowing candidates to browse and apply for jobs, while recruiters/admins can manage job postings, review applications, and control the entire workflow from a centralized dashboard.

---

## 🚀 Features

### 👤 Authentication & Authorization
- JWT-based login system  
- Role-based access: **Candidate**, **Recruiter**, **Admin**  
- Secure API access using Spring Security  

### 📄 Job Management
- Create, update, publish, and archive job postings  
- Pagination & filters for job listings  
- Detailed job description pages  

### 📝 Candidate Module
- Create profile and upload resume  
- Apply to jobs  
- Track application status  
- View history of applied jobs  

### 🧑‍💼 Recruiter/Admin Dashboard
- View all applicants per job  
- Filter candidates based on skills, experience, and status  
- Shortlist, reject, and manage candidate workflow  
- Manage job postings in one place  

### 🔍 Search & Filters
- Search by job title, skills, or location  
- Filter by experience, job type, salary range  

---

## 🛠️ Tech Stack

### **Frontend**
- React.js  
- React Router  
- Axios  
- TailwindCSS / Material UI  

### **Backend**
- Spring Boot  
- Spring MVC  
- Spring Security (JWT)  
- Spring Data JPA  
- Hibernate  
- MySQL / PostgreSQL  

### **Tools**
- Maven  
- Git & GitHub  
- Postman  

## 📁 Project Structure

### Frontend
/frontend
├── public
├── src
│ ├── components
│ ├── pages
│ ├── services
│ ├── context
│ ├── hooks
│ └── App.js
└── package.json

shell
Copy code

### Backend
/backend
├── src/main/java/com/project
│ ├── controller
│ ├── service
│ ├── repository
│ ├── model
│ ├── security
│ └── RecruitmentPortalApplication.java
├── src/main/resources
│ └── application.properties
└── pom.xml

🎯 Backend Setup (Spring Boot)
2️⃣ Configure Database

Update application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/recruitment_portal
spring.datasource.username=your_username
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

3️⃣ Start Backend
mvn spring-boot:run

Backend runs on:
➡️ http://localhost:8080

💻 Frontend Setup (React)

4️⃣ Install Dependencies
cd frontend
npm install

5️⃣ Start Frontend
npm start

Frontend runs on:
➡️ http://localhost:3000

