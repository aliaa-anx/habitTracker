# Habit Builder - Backend

**Habit Builder** is a backend service for a habit-tracking application. It allows users to build positive routines by creating habits, joining challenges, setting goals, and receiving reminders. This backend is built using **Spring Boot** with a domain-centric architecture for clean separation of concerns.

## ✨ Features

- ✅ Create and manage personal habits
- 🏆 Join and track challenge participation
- 🎯 Set goals and monitor progress
- ⏰ Schedule and receive habit reminders
- 📦 Modular, domain-driven structure for scalability and maintainability

## 🧱 Tech Stack

- **Java 17**
- **Spring Boot**
- **Maven**
- **JPA (Hibernate)**
- **MySQL/PostgreSQL** (or configurable DB)
- **Docker** (if applicable for deployment)
- **Clean Architecture Principles**

## 📁 Project Structure

habit-builder/
├── src/
│ ├── main/
│ │ ├── java/com/habitBuilder/habit_builder/
│ │ │ ├── application/service/ # Application-level services
│ │ │ ├── domain/ # Domain models & logic
│ │ │ ├── infrastructure/ # Repositories, config, etc.
│ │ │ └── HabitBuilderApplication.java
│ └── test/ # Unit and integration tests
├── pom.xml # Maven configuration
└── .gitignore, README.md, etc.
