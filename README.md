# Task Manager Backend (Spring Boot + MySQL)

## Overview

This is a RESTful backend application for managing tasks.
It supports full CRUD operations with proper validation and exception handling.

---

## Tech Stack

* Java
* Spring Boot
* Spring Data JPA
* MySQL
* Maven

---

## Features

* Create, Read, Update, Delete tasks
* DTO-based API design
* Input validation using Jakarta Validation
* Global exception handling
* Clean layered architecture

---

## API Endpoints

| Method | Endpoint    | Description    |
| ------ | ----------- | -------------- |
| POST   | /tasks      | Create a task  |
| GET    | /tasks      | Get all tasks  |
| GET    | /tasks/{id} | Get task by ID |
| PUT    | /tasks/{id} | Update task    |
| DELETE | /tasks/{id} | Delete task    |

---

## How to Run

1. Clone the repo
2. Configure MySQL in `application.properties`
3. Run the Spring Boot application

---

## Future Improvements

* Add user authentication (JWT)
* Add deadlines & reminders
* Build frontend (React)

---
