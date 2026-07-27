# Student Record Management System

## Overview
The Student Management System is a Java console-based application that allows users to manage student records efficiently. It provides basic CRUD (Create, Read, Update, Delete) operations through a menu-driven interface. Student information is stored in an `ArrayList`, making it suitable for learning Java collections and object-oriented programming concepts.

## Features
- Add new student records
- View all student records
- Update existing student details
- Delete student records
- Prevent duplicate student IDs
- Menu-driven command-line interface

## Technologies Used
- Java
- ArrayList
- Object-Oriented Programming (OOP)
- Scanner Class
- VS Code / IntelliJ IDEA Community Edition

## Project Structure

```
StudentManagementSystem/
│
└── StudentManagementSystem.java
```

## Student Details
Each student record contains:
- Student ID
- Student Name
- Student Marks

## Requirements
- Java JDK 8 or above
- VS Code / IntelliJ IDEA / Eclipse

## How to Run

### Compile

```bash
javac StudentManagementSystem.java
```

### Run

```bash
java StudentManagementSystem
```

## Menu Options

```
===== Student Record Management System =====

1. Add Student
2. View Students
3. Update Student
4. Delete Student
5. Exit
```

## Sample Output

```
===== Student Record Management System =====

1. Add Student
2. View Students
3. Update Student
4. Delete Student
5. Exit

Enter your choice: 1

Enter Student ID: 101
Enter Student Name: John
Enter Student Marks: 89

Student Added Successfully!
```

## Concepts Used
- Classes and Objects
- Constructors
- Encapsulation
- ArrayList
- Methods
- Loops
- Conditional Statements
- User Input using Scanner

## Learning Outcomes
After completing this project, students will understand:
- Java Object-Oriented Programming
- CRUD Operations
- Dynamic Data Storage using ArrayList
- Console-based Application Development
- Menu-driven Program Design

## Future Enhancements
- Store records in a database (SQLite/MySQL)
- File handling for data persistence
- Search student by ID or Name
- Sort students by marks or name
- Java Swing/JavaFX GUI version
- Student report generation

