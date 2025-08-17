# Education-Online-Learning-Platform-Microservices-Project

This project is a **Microservices-based Online Learning Platform** built using **Spring Boot, REST APIs, and MongoDB**.  
It allows students to **enroll in courses, manage enrollments, and demonstrates inter-service communication** using `RestTemplate`.

---

## 🚀 Features
- **Student Service**: Manages student details.
- **Course Service**: Manages course information.
- **Enrollment Service**: Handles student enrollments into courses.
- **Microservices Communication**: Implemented using `RestTemplate`.
- **MongoDB Integration**: Stores and retrieves data efficiently.
- **CRUD Operations**: Full Create, Read, Update, Delete support.
---

## 🏗️ Project Architecture
Student Service --->
\
---> Enrollment Service ---> MongoDB
/
Course Service --->
---

## 🛠️ Tech Stack
- **Java 17**  
- **Spring Boot 3.x**  
- **Spring Data MongoDB**  
- **Spring Web (REST APIs)**  
- **Maven**  
- **Eclipse/STS IDE**  
- **Git & GitHub**

---
## 📂 Microservices Structure
education-platform/
│── student-service/ # Handles student data
│── course-service/ # Handles course data
│── enrollment-service/ # Manages student enrollments
│── README.md # Documentation


---

## ⚡ API Endpoints

### Student Service (Port: 2001)
- `GET /student/get/{id}` → Get student by ID  
- `POST /student/add` → Add new student  

### Course Service (Port: 2002)
- `GET /course/get/{id}` → Get course by ID  
- `POST /course/add` → Add new course  

### Enrollment Service (Port: 2003)
- `POST /enroll/add` → Enroll a student into a course  
- `GET /enroll/get/{id}` → Get enrollment by ID  
- `GET /enroll/getall` → Get all enrollments  
- `PUT /enroll/update` → Update enrollment  
- `DELETE /enroll/delete/{id}` → Delete enrollment  

---

## ▶️ How to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/Education-Online-Learning-Platform-Microservices-Project.git
   cd Education-Online-Learning-Platform-Microservices-Project
Run MongoDB

Start MongoDB locally on localhost:27017.

Start Each Microservice

Open each service (student-service, course-service, enrollment-service) in Eclipse/STS.

Run as Spring Boot Application.

Ports:

Student Service → 2001

Course Service → 2002

Enrollment Service → 2003

Test APIs

Use Postman or browser to test endpoints.

📌 Future Enhancements

Replace RestTemplate with Spring Cloud OpenFeign.

Implement Spring Cloud Config for centralized configuration.

Add API Gateway & Eureka Service Discovery.

Secure APIs using Spring Security + JWT.

Dockerize microservices for deployment.

🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

👨‍💻 Author

Your Name
📧 Email: your.email@example.com
🔗 GitHub: your-username


👉 This is in **GitHub Markdown language** (with `#`, `##`, code blocks, lists, emojis, etc.) — it will look very professional on GitHub.  

Do you want me to also **customize with your real name, email, and GitHub profile link** so it’s ready to upload directly?



