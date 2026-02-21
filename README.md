Student Management System (C# Console App)
Overview

This is a simple Student Management System built in C# as a console application. It allows an administrator to manage student records including adding, viewing, searching, updating, deleting students, calculating class averages, and sorting students by marks. The data is stored locally in a text file (students.txt) for persistence.

Features

Admin Login: Secure login with hardcoded credentials (admin / 123).

Add Student: Add new student records with Roll Number, Name, Age, and Marks.

Display Students: View all student records along with their grades.

Search Student: Find a student by Roll Number.

Update Student: Update existing student details.

Delete Student: Remove a student record.

Class Average: Calculate the average marks of all students.

Sort by Marks: Display students sorted by their marks in descending order.

Persistent Storage: All student data is saved in students.txt.

Requirements

.NET Framework (Console App compatible) or .NET Core SDK

Windows, Linux, or macOS machine with console access.

Installation

Clone or download the project.

Open the folder in Visual Studio or any C# IDE.

Build the solution.

Ensure students.txt exists in the project folder (it will be auto-created if missing).

Run the program.

Usage

Run the program.

Enter admin credentials:

Username: admin
Password: 123

Use the menu to perform operations:

1. Add Student
2. Display Students
3. Search Student
4. Update Student
5. Delete Student
6. Class Average
7. Sort by Marks
8. Exit

Input required data for each operation when prompted.

Exit the program using option 8 (data will automatically be saved).

File Structure
StudentManagementSystem/
│
├─ Program.cs           # Main application logic
├─ Student.cs           # Student class definition
├─ students.txt         # Data file for storing student records
└─ README.md            # Project documentation
Student Class Properties
Property	Type	Description
Roll	int	Student Roll Number
Name	string	Student Name
Age	int	Student Age
Marks	double	Student Marks
Grade	string	Computed grade based on Marks

Grade Calculation:

90+ : A+

80–89 : A

70–79 : B

60–69 : C

50–59 : D

<50 : F

Example

Adding a Student:

Enter Roll: 101
Enter Name: Ali
Enter Age: 20
Enter Marks: 85
✅ Student Added!

Displaying Students:

Roll: 101, Name: Ali, Age: 20, Marks: 85, Grade: A

Class Average:

Class Average = 85
Notes

Ensure numeric inputs for Roll, Age, and Marks. Non-numeric input will prompt for re-entry.

All student data is saved in CSV format in students.txt and loaded automatically at program start.

Author

Maira Bibi – Developer

If you want, I can also make a shorter, GitHub-ready version with badges and quick setup instructions so you can directly upload it as README.md.
