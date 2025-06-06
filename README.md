# Habit Builder - Backend

**Habit Builder** is a backend REST API built using **Spring Boot** and designed following **Clean Architecture** principles. It supports dynamic habit creation, goal setting, challenge participation, and reminders—ideal for helping users build and maintain positive habits.

---

## 🧠 Architectural Overview

This project is structured using **Clean Architecture**, which separates concerns into distinct layers:

- **Domain Layer**: Business logic and core entities
- **Application Layer**: Use cases and service orchestration
- **Infrastructure Layer**: Persistence (JPA), configuration, and integration
- **presentation Layer**: restful API end points


This separation ensures the system is **testable**, **scalable**, and **easy to maintain**.

---

## 🚀 Built With

- **Java 17**
- **Spring Boot** – rapid development with production-grade features
- **Spring Data JPA** – for ORM and database interactions
- **Maven** – project and dependency management
- **MySQL / PostgreSQL** – relational database support


---



## 📁 Clean Architecture Project Structure

habit-builder/
├── domain/ # Core business models and logic
├── application/ # Use cases and services
├── infrastructure/ # Repositories, config, external adapters
├── HabitBuilderApplication # Spring Boot application entrypoint
├── resources/ # application.properties, static configs
└── test/ # Unit and integration tests


---

## 🧰 Getting Started

### Prerequisites

- Java 17+
- Maven 3.8+
- A relational database (MySQL, PostgreSQL)

### Run Locally

1. **Configure the database** in `src/main/resources/application.properties`:

   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/habit_builder
   spring.datasource.username=root
   spring.datasource.password=yourpassword
   spring.jpa.hibernate.ddl-auto=update

   
📦 Features
 Habit Creation & Tracking

 Goal Management

 Challenge Participation

 Reminder Scheduling
 
 Clean Architecture with Spring Boot

  Built-in Testing Support

📌 REST API Endpoints

The API provides endpoints for:

/habits

/goals

/reminders

/challenges

/templates
