
---

## Hotel Booking System

This is a full-stack Hotel Booking web application built with **Spring Boot** for the backend and **React** for the frontend. The system supports room listings, user authentication, booking management, and admin operations.

---

### Features

**User Side**

* Browse available rooms
* Book rooms with check-in/check-out dates
* View and manage personal bookings
* User registration and secure login

**Admin Side**

* Add/edit/delete rooms
* View all bookings
* Manage notifications via Email/SMS/WhatsApp
* Secure authentication using JWT

**Additional Functionality**

* Room image upload support
* RESTful APIs with role-based access control
* Centralized error handling
* MongoDB or SQL integration (as per environment)

---

### Tech Stack

**Frontend**

* React
* React Router
* Axios
* HTML, CSS, JavaScript

**Backend**

* Java 18
* Spring Boot
* Spring Security (JWT)
* JPA/Hibernate
* MySQL / H2 (for development)
* Lombok

**Tools & Libraries**

* Postman (API testing)
* Maven or Gradle (build tools)
* Git & GitHub (version control)
* IntelliJ IDEA

---

### Folder Structure

```
HotelBookingProject/
├── backend/
│   ├── src/
│   ├── build/
│   ├── target/
│   └── application.properties
├── frontend/
│   ├── public/
│   ├── src/
│   └── package.json
```

---

### Getting Started

#### Prerequisites

* Java 18+
* Node.js and npm
* MySQL or H2 database
* Git

#### Run Backend

```bash
cd backend
./mvnw spring-boot:run
```

or if using Gradle:

```bash
./gradlew bootRun
```

#### Run Frontend

```bash
cd frontend
npm install
npm start
```

---

### API Endpoints (Sample)

* `POST /api/auth/register` – Register user
* `POST /api/auth/login` – Login
* `GET /api/rooms` – View available rooms
* `POST /api/bookings` – Book a room
* `POST /api/notifications/email` – Send email notification

---

### Security

* JWT-based Authentication
* Role-based Access Control (`USER`, `ADMIN`)
* Password encryption using BCrypt
* Secret keys managed via `.env` or `application.properties`

---


### License

This project is open-source and available under the [MIT License](LICENSE).

---


