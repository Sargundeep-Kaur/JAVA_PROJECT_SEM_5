# Expense Tracker Pro

A full-stack Expense Tracker application built using React and Spring Boot. The project aims to provide a platform for managing and tracking expenses with a modern frontend and a Java-based backend.

## Tech Stack

### Frontend
- React.js
- Vite
- JavaScript
- Tailwind CSS
- Axios
- Chart.js

### Backend
- Java 17
- Spring Boot
- Spring Data JPA
- Spring Web MVC
- Maven

### Database
- MySQL

## Project Structure

```text
Expense-Tracker-Pro/
│
├── client/          # React frontend
│
├── server/          # Spring Boot backend
│
├── .gitignore
└── README.md
```

## Getting Started

### 1. Clone the Repository

```bash

git clone https://github.com/Sargundeep-Kaur/JAVA_PROJECT_SEM_5.git
cd JAVA_PROJECT_SEM_5
```

### 2. Run the Frontend

```bash
cd client
npm install
npm run dev
```

### 3. Run the Backend

Open another terminal:

```bash
cd server
./mvnw spring-boot:run
```

On Windows, use:

```bash
mvnw.cmd spring-boot:run
```

## Database Configuration

Make sure MySQL is installed and running.

Configure your database connection in the backend's `application.properties` file.

Add your own database name, username, and password. Do not commit private credentials to GitHub.

## Technologies & Tools

- React.js for building the user interface
- Spring Boot for backend development
- Spring Data JPA for database interaction
- MySQL for data storage
- Maven for dependency management

## Author
Sargundeep Kaur

Developed as a full-stack development project.
