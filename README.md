# 🎓 Student Management System (Console App - C#)

## 📌 Project Overview

This is a simple **Student Management System** built using C# as a console application.
The program allows users to manage student records by performing basic operations such as adding, viewing, searching, and deleting students.

---

## 🎯 Purpose of the Project

The goal of this project is to practice and understand core C# programming concepts, including:

* Classes and Objects
* Lists and Collections (`List<T>`)
* User Input and Output
* Control Structures (loops and conditionals)
* Basic CRUD operations (Create, Read, Update, Delete)

---

## ⚙️ Features

The application provides the following functionality:

1. **Add Student**

   * Enter student ID, name, and age
   * Store student in memory

2. **View Students**

   * Display all students in the system

3. **Search Student**

   * Find a student using their ID

4. **Delete Student**

   * Remove a student from the system

5. **Exit**

   * Close the application

---

## 🧱 Technologies Used

* C#
* .NET Console Application
* Visual Studio

---

## 🧠 Concepts Implemented

### 1. Class Definition

A `Student` class is used to represent student data:

* Id
* Name
* Age

### 2. Data Storage

* A `List<Student>` is used to store student records during runtime.

### 3. Control Flow

* `while(true)` loop keeps the application running
* `switch` statement handles menu options

### 4. User Interaction

* `Console.ReadLine()` for input
* `Console.WriteLine()` for output

---

## ▶️ How to Run the Application

1. Open the project in Visual Studio
2. Build the solution
3. Run the program
4. Follow the menu instructions in the console

---

## ⚠️ Limitations

* Data is not saved permanently (resets when program closes)
* No input validation (invalid inputs may cause errors)
* No update functionality yet

---

## 🚀 Future Improvements

* Add input validation using `int.TryParse()`
* Prevent duplicate student IDs
* Add "Update Student" feature
* Save data to a file or database
* Improve user interface

---

## 📚 What I Learned

* How to structure a simple console application
* How to use lists to store objects
* How to handle user input
* How to implement basic CRUD operations in C#

---

## 👨‍💻 Author

* Lazarus Tshabadira Motsalane

---
