# 🎬 Movie Ticket Booking Platform (BMS)

A full-stack **Book My Show-style** movie ticket booking system built with **Spring Boot** (Java 21) and a vanilla HTML/CSS/JS frontend.

---

## 🚀 Tech Stack

| Layer        | Technology                          |
|--------------|-------------------------------------|
| Backend      | Spring Boot 4.0.3, Java 21          |
| ORM          | Spring Data JPA (Hibernate)         |
| Database     | MySQL                               |
| Security     | Spring Security                     |
| Frontend     | HTML, CSS, JavaScript               |
| Build Tool   | Maven (Maven Wrapper included)      |
| Utilities    | Lombok                              |

---

## 📁 Project Structure

```
Movie-Ticket-Booking-Platform/
├── src/
│   └── main/
│       ├── java/com/cfs/BMS/       # Spring Boot application source
│       └── resources/              # application.properties, static files
├── UI/
│   └── UI/                         # Frontend HTML/CSS/JS files
├── pom.xml                         # Maven dependencies & build config
└── mvnw / mvnw.cmd                 # Maven wrapper scripts
```

---

## ⚙️ Prerequisites

- Java 21+
- MySQL 8+
- Maven (or use the included `mvnw` wrapper)

---

## 🛠️ Setup & Run

### 1. Clone the repository

```bash
git clone https://github.com/nik1910-sd/Movie-Ticket-Booking-Platform.git
cd Movie-Ticket-Booking-Platform
```

### 2. Configure the database

Create a MySQL database and update `src/main/resources/application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/bms_db
spring.datasource.username=your_username
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
```

### 3. Run the application

```bash
./mvnw spring-boot:run
```

Or on Windows:

```cmd
mvnw.cmd spring-boot:run
```

The server starts at `http://localhost:8080`.

---

## ✨ Features

- Browse movies and showtimes
- Seat selection and ticket booking
- User authentication via Spring Security
- RESTful backend APIs consumed by the frontend
- Persistent data storage with MySQL via JPA

---

## 🧪 Running Tests

```bash
./mvnw test
```

---

## 📌 Notes

- Spring Boot DevTools is included for hot-reload during development.
- The frontend (HTML/CSS/JS) lives in the `UI/` folder and communicates with the backend via REST APIs.

---

## 👤 Author

**Nikhil Kumar** — [GitHub](https://github.com/nik1910-sd)
 — [LinkedIn](https://www.linkedin.com/in/nikhil-kumar-5a1584223)
