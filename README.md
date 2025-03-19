

# **Social Media Backend (Spring Boot)**

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-2.7.5-brightgreen.svg) ![Java](https://img.shields.io/badge/Java-17-blue.svg) ![Maven](https://img.shields.io/badge/Maven-Build-orange.svg)

## **📌 Overview**
This is a **social media backend** built with **Spring Boot**, providing REST APIs for user authentication, posts, comments, and interactions.

---

## **🚀 Features**
- ✅ User Authentication (JWT-based)
- ✅ Create, Read, Update, and Delete (CRUD) posts
- ✅ Comments and Likes functionality
- ✅ Follows and Friend Requests
- ✅ Secure API with Spring Security
- ✅ Database integration with **MySQL/PostgreSQL**
- ✅ API Documentation using **Swagger**

---

## **🛠️ Tech Stack**
- **Java 17**
- **Spring Boot**
- **Spring Security**
- **Spring Data JPA**
- **Hibernate**
- **Maven**
- **MySQL/PostgreSQL**
- **JWT Authentication**

---

## **📂 Project Structure**
```
backend
│── src
│   ├── main
│   │   ├── java/com/example/socialmedia
│   │   │   ├── controllers
│   │   │   ├── services
│   │   │   ├── repositories
│   │   │   ├── models
│   │   │   ├── config
│   │   ├── resources
│   │   │   ├── application.properties
│   │── test
│── pom.xml
│── README.md
```

---

## **⚡ Installation and Setup**
### **1️⃣ Clone the Repository**
```bash[
git clone  https://github.com/demonssvz/socialMediaBackend.git 
cd backend
```

### **2️⃣ Configure Database**
Edit **`src/main/resources/application.properties`**:

```
spring.datasource.url=jdbc:mysql://localhost:3306/social_media_db
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update
```

### **3️⃣ Build & Run the Application**
```bash
mvn clean install
mvn spring-boot:run
```

---
 

## **📌 Contributing**
Contributions are welcome! Feel free to fork this repo and submit a pull request.

 
