 QuickServe – Service Booking Application (Java Full Stack)

📌 Project Overview

QuickServe is a full-stack Service Booking Application developed using Java technologies.
It allows users to register, browse services, book appointments, make payments, and manage booking history.
The system also includes an Admin panel for managing services, users, and bookings.
 
  Features

 User Features

* User Registration & Login (JWT Authentication)
* Browse Available Services
* View Service Provider Details
* Book Services (Date & Time Selection)
* Secure Payment Integration
* View Booking History
* Rate & Review Services

 Admin Features

* Admin Login
* Add / Update / Delete Services
* Manage Service Providers
* View All Bookings
* Manage Users
* Dashboard with Booking Statistics

 
 Tech Stack

🔹 Frontend

* HTML5
* CSS3
* JavaScript
* React.js (if used)
* Axios (API communication)

🔹 Backend

* Java
* Spring Boot
* Spring MVC
* Spring Data JPA
* Hibernate
* REST APIs

🔹 Database

* MySQL

🔹 Security

* Spring Security
* JWT Authentication
* Role-Based Authorization (Admin/User)

🔹 Tools & Others

* Maven
* Thunderclient (API Testing)
* Git & GitHub
* IntelliJ / Eclipse / VS Code

 📂 Project Structure

```
quickserve/
│
├── backend/
│   ├── controller/
│   ├── service/
│   ├── repository/
│   ├── model/
│   ├── config/
│   └── QuickServeApplication.java
│
├── frontend/
│   ├── components/
│   ├── pages/
│   ├── services/
│   └── App.js
│
└── README.md
```

  Application Workflow

1. User registers and logs in.
2. User browses services.
3. User selects service and books appointment.
4. Payment is processed.
5. Booking details are stored in database.
6. Admin monitors bookings and manages services.

  Database Schema 

* Users
* Roles
* Services
* Bookings
* Payments
* Reviews

  Authentication Flow

* User logs in with credentials.
* Backend validates credentials.
* JWT Token is generated.
* Token is stored on client side.
* Token is sent in Authorization header for protected routes.

  Installation & Setup

 🔹 Backend Setup

1. Clone the repository

```bash
git clone https://github.com/your-username/quickserve.git
```

2. Navigate to backend folder

```bash
cd backend
```

3. Configure `application.properties`

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/quickserve
spring.datasource.username=root
spring.datasource.password=yourpassword
```

4. Run the application

```bash
mvn spring-boot:run
```

Backend runs on:

```
http://localhost:8080
```

---


1. Navigate to frontend folder

```bash
cd frontend
```

2. Install dependencies

```bash
npm install
```

3. Start the frontend

```bash
npm start
```

 Testing

* API Testing using Postman
* Manual UI Testing
* Validation & Error Handling Implemented

 

 
