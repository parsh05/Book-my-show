# 🎬 BookMyShow APIs – Spring Boot Project

This project is a **Spring Boot backend implementation** for a movie and event ticket booking system inspired by _BookMyShow_. It provides a set of **RESTful APIs** that allow users and admins to manage movies, theaters, seats, and ticket bookings.

---

## ✨ Features

- **User Management**

  - Register and log in
  - Manage personal profile

- **Movie Management (Admin)**

  - Add, update, and remove movies

- **Theater Management (Admin)**

  - Add and edit theaters
  - Allocate seats
  - Remove theaters

- **Ticket Booking**

  - Browse available movies/events
  - Book tickets for a specific event

- **Seat Selection**

  - Choose preferred seats from available options

- **Booking History**

  - View past bookings and details

- **Email Notifications**
  - Receive email confirmations for successful bookings
  - Get updates on important changes

---

## 🛠️ Tech Stack

- **Java 8+**
- **Spring Boot**
- **Spring MVC**
- **Spring Data JPA**
- **MySQL** (Database)
- **Maven** (Dependency Management)
- **SMTP Server** (Email Notifications)

---

## 🚀 Getting Started

Follow these steps to set up the project locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/parshant05/Book-My-Show.git

   ```

2. Navigate to the project directory:

   ```bash
   cd book-my-show

   ```

3. Configure database settings in the application.properties file.
4. Build the project with Maven:
   ```bash
   mvn clean install
   ```
5. Run the application:
   ```bash
   mvn spring-boot:run
   ```
6. Access the app at: http://localhost:8080

## 🗄️ Database Setup

This project uses MySQL. To set it up:

1. Install MySQL locally
2. Create a new database:
   ```bash
   CREATE DATABASE bookMyShowDB;
3. Update the credentials in 
    ```bash 
    application.properties

## 📖 API Documentation

API documentation is available via Swagger UI at:
👉 http://localhost:8080/swagger-ui.html

This includes details for all endpoints, request/response formats, and parameters.
