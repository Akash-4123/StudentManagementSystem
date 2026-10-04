# 🎓 Student Management System

A console-based **Student Management System** developed using **Core Java, JDBC, MySQL, and Gradle**.  
The application provides a simple and structured way to manage student records through CRUD operations.

---

## 📌 Project Overview

The Student Management System is a Java-based application designed to manage student information efficiently.

It allows users to:

- ➕ Add new students
- 📋 View all students
- 🔍 Search students by ID
- ✏️ Update student details
- 🗑️ Delete student records

The application uses **JDBC** to connect the Java application with a **MySQL database**, allowing student information to be stored and managed persistently.

---

## 🚀 Features

### 👨‍🎓 Student Management
- Add student details
- View all registered students
- Search students using Student ID
- Update existing student information
- Delete student records

### 🗄️ Database Integration
- MySQL database for persistent data storage
- JDBC for database connectivity
- SQL queries for CRUD operations

### ⚙️ Project Management
- Gradle-based project
- Gradle Wrapper included
- Organized Java package structure
- Git and GitHub version control

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| ☕ Java | Application development |
| 🔗 JDBC | Database connectivity |
| 🐬 MySQL | Data storage |
| 📦 Gradle | Build and dependency management |
| 🔧 Git | Version control |
| 🌐 GitHub | Source code hosting |
| 💻 IntelliJ IDEA | Development environment |

---

## 🏗️ Project Structure

```text
StudentManagementSystem/
│
├── src/
│   └── main/
│       └── java/
│           └── com/
│               └── akash/
│                   └── studentmanagement/
│                       ├── DBConnection.java
│                       ├── Student.java
│                       └── StudentManagementSystem.java
│
├── gradle/
├── build.gradle
├── settings.gradle
├── gradlew
├── gradlew.bat
├── .gitignore
└── README.md