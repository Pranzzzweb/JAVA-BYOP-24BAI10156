# 📚 Course & Student Management System (Java)

## 📌 Overview

This project is a Java-based application designed to manage students, courses, and enrollments in an organized and efficient way. It simulates a real-world academic management system where students can be enrolled in courses, and their data can be stored, retrieved, and managed easily.

The project focuses on applying core Object-Oriented Programming (OOP) concepts and file handling in Java to solve a practical problem faced in educational institutions.

---

## ❗ Problem Statement

In many small institutions or informal setups, managing student records and course enrollments is often done manually, leading to errors, redundancy, and inefficiency.

This project aims to provide a simple system to:

* Store student and course data
* Manage enrollments
* Avoid duplication and maintain consistency

---

## 🎯 Objectives

* To implement a structured system for managing students and courses
* To apply OOP concepts like classes, inheritance, and encapsulation
* To handle data storage using file handling
* To ensure validation and error handling in operations

---

## ⚙️ Features

* 👤 Student Management

  * Add and manage student details
  * Unique identification for each student

* 📖 Course Management

  * Create and manage courses
  * Store course-related information

* 🔗 Enrollment System

  * Enroll students into courses
  * Prevent duplicate enrollments
  * Enforce credit limits

* 💾 File Handling

  * Import/export data using CSV files
  * Backup functionality

* ⚠️ Exception Handling

  * Handles cases like duplicate enrollment
  * Credit limit exceeded validation

---

## 🛠️ Technologies Used

* Java
* Object-Oriented Programming (OOP)
* File Handling (CSV)
* Exception Handling

---

## 📂 Project Structure

```id="r9mq1p"
src/
 └── edu/ccrm/
      ├── domain/        # Core classes (Student, Course, etc.)
      ├── service/       # Business logic (Enrollment, Course handling)
      ├── io/            # File handling (Import/Export, Backup)
      ├── util/          # Utility classes (Validation, Recursion)
test-data/               # Sample CSV data
```

---

## ▶️ How to Run

1. Clone the repository:

```id="3bq9gd"
git clone https://github.com/your-username/your-repo-name.git
```

2. Navigate to the project folder:

```id="1y9rpn"
cd your-repo-name
```

3. Compile the project:

```id="d4fh4x"
javac -d . src/edu/ccrm/**/*.java
```

4. Run the main class:

```id="f2k8nl"
java edu.ccrm.Main
```

---

## 🚧 Challenges Faced

* Managing relationships between students, courses, and enrollments
* Implementing proper validation without overcomplicating logic
* Handling file input/output efficiently
* Designing a modular and scalable structure

---

## 📈 Future Improvements

* Add a graphical user interface (GUI)
* Integrate with a database instead of CSV files
* Add authentication system for admin/users
* Improve user interaction and reporting features

---

## 📚 What I Learned

* Practical implementation of OOP concepts
* Structuring a real-world Java project
* Handling data using file operations
* Writing clean, modular, and maintainable code

---

## 👤 Author

**Pranjali Sharma
  24BAI10156**

---

## 📌 Note

This project was developed as part of a BYOP (Bring Your Own Project) assignment to apply Java programming concepts in a real-world scenario.
