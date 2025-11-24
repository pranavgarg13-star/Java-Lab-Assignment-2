# Java-Assignment
By : Pranav Garg , Roll No. : 2401010034
Advanced Student Management System

This is a menu-driven Java application that demonstrates Object-Oriented Programming concepts including:
  -  Abstract classes
  -  Inheritance
  -  Method overloading & overriding
  - Interfaces
  - Maps (HashMap)
  - Final methods
  - Garbage collection (finalize() method)
  - CRUD Operations (Create, Read, Update, Delete)

The system allows users to maintain student records effectively using a hashmap and interactive console menu.

##  Features
- Student Operations
- Add new student
- Delete student
- Update student details
- Search student by roll number
- View all students
- OOP Concepts Used
- Abstract Class – Person
- Contains name, email
- Abstract displayInfo() method
- Final method
- finalize() method demonstrates garbage collection
- Student Class
- Inherits from Person
- Constructor overloading
- Method overloading (displayInfo(String note))
- Method overriding (custom displayInfo())

## Class Overview
1. Class	Description
2. Person	Abstract parent class with common attributes
3. Student	Child class with roll no, course, marks, grade
4. RecordActions	Interface for CRUD operations
5. StudentManager	Implements interface using HashMap
6. StudentManagement	Main class with menu-driven program
## How to Run
1. Compile the program : javac StudentManagement.java
2. Run it : java StudentManagement

## Sample Interaction

===== Student Management Menu =====

1. Add Student
2. Delete Student
3. Update Student
4. Search Student
5. View All Students
6. Exit
   
Enter Choice: 1

Roll No: 101

Name: Arjun

Email: arjun@gmail.com

Course: BCA

Marks: 88

Student Added Successfully!


Enter Choice: 4

Enter Roll No: 101


Student Info:

Roll No : 101

Name    : Arjun

Email   : arjun@gmail.com

Course  : BCA

Marks   : 88.0

Grade   : B


Enter Choice: 5

(Displays all students with details)
