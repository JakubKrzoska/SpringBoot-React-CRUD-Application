# 🚀 Spring Boot & React CRUD Application

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)

> A full-stack web application demonstrating complete Create, Read, Update, and Delete (CRUD) operations using a Java Spring Boot backend and a React.js frontend.

## 📝 Project Description

This project serves as a comprehensive full-stack template and demonstration of integrating a modern **React frontend** with a robust **Java Spring Boot backend**. It handles seamless data flow from a user-friendly UI all the way to a relational database. The application is cleanly divided into two separate architectures: `fullstack-front` (client-side) and `fullstack-backend` (server-side).

## ✨ Key Features

- **Full CRUD Functionality:** Users can seamlessly create new records, view existing data, update information, and delete entries.
- **RESTful API:** A well-structured Spring Boot backend exposing clear and secure endpoints for client consumption.
- **Reactive UI:** Instant UI updates and state management handled efficiently by React Hooks.
- **Cross-Origin Communication:** Properly configured CORS bridging the gap between the `localhost` React server and the Spring Boot API.

## 🛠️ Technologies Used

### Frontend (`fullstack-front`)

- **Library:** React.js
- **Routing:** React Router DOM
- **HTTP Client:** Axios
- **Styling:** CSS / Bootstrap

### Backend (`fullstack-backend`)

- **Framework:** Spring Boot (Java)
- **Build Tool:** Maven
- **Data Access:** Spring Data JPA / Hibernate
- **Database:** MySQL

## 🧠 What I Learned

Building this application bridged the gap between enterprise Java development and modern frontend frameworks. Key takeaways include:

- **Spring Boot Architecture:** Understanding the Controller, Service, and Repository layers in Java, and using Spring Data JPA to reduce boilerplate SQL code.
- **API Integration:** Mastering how to effectively consume RESTful APIs using React, handling asynchronous data fetching, and managing loading/error states.
- **CORS Management:** Successfully configuring Cross-Origin Resource Sharing (CORS) in Spring Boot to allow the React frontend to communicate with the backend securely.
- **Project Configuration:** Managing a monorepo-style setup with separate Node.js (`npm`) and Java (`Maven`) build processes.

## 📷 Screenshots

![java fullstack1](/fullstack-front/public/java_fullstack.png)
![java fullstack2](/fullstack-front/public/java_fullstack2.png)

## 🚀 How It Works & Getting Started

To get a local copy up and running, follow these steps.

### Prerequisites

- [Java Development Kit (JDK) 17+](https://www.oracle.com/java/technologies/javase-downloads.html) installed.
- [Node.js](https://nodejs.org/) installed.
- A local SQL database server running (e.g., MySQL or PostgreSQL).

Open a terminal and navigate to the backend directory:

```bash
cd fullstack-backend
```
