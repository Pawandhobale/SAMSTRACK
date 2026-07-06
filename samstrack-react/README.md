# SamsTrack API

## About the Project

**SamsTrack API** is a Spring Boot REST API application developed to manage student attendance in educational institutions. It provides APIs to manage students, subjects, faculty, attendance records, and users. The system helps automate attendance tracking, improve data accuracy, and simplify academic record management.

---

## Features

* Student Management
* Subject Management
* Faculty Management
* Attendance Management
* User Registration & Login
* CRUD REST APIs
* MySQL Database Integration

---

## Tech Stack

* Java 8
* Spring Boot 2.5.6
* Spring Data JPA
* Hibernate
* MySQL 8
* Maven
* Eclipse
* Postman

---

## Project Modules

* Student Module
* Subject Module
* Faculty Module
* Attendance Module
* User Module

---

## Project Structure

```
Controller
    ↓
Service
    ↓
DAO (Repository)
    ↓
MySQL Database
```

---

## REST APIs

### Student

* GET /student/get-all-students
* GET /student/get-student-by-id/{id}
* POST /student/add-student
* PUT /student/update-student
* DELETE /student/delete-student/{id}

### Subject

* GET /subject/get-all-subjects
* GET /subject/get-subject-by-id/{id}
* POST /subject/add-subject
* PUT /subject/update-subject
* DELETE /subject/delete-subject/{id}

### Faculty

* GET /faculty/get-all-faculties
* GET /faculty/get-faculty-by-id/{id}
* POST /faculty/add-faculty
* PUT /faculty/update-faculty
* DELETE /faculty/delete-faculty/{id}

### Attendance

* GET /attendance/get-all-attendance-records
* POST /attendance/add-attendance

### User

* POST /user/register-user
* POST /user/login-user
* GET /user/get-user-by-username/{username}
* GET /user/get-all-user
* DELETE /user/delete-user

---

## Database

MySQL

Configure database settings in:

```
src/main/resources/application.properties
```

---

## Run the Project

```bash
mvn spring-boot:run
```

Default Server:

```
http://localhost:8091
```

---

## Author

**Pawan Dhobale**
Java Backend Developer
