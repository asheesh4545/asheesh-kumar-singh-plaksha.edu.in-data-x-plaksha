# asheesh-kumar-singh-plaksha.edu.in-data-x-plakshaSQL Assignment - Plaksha University
Overview
This assignment is aimed at practicing SQL skills, including table creation, data querying, and the use of aggregate functions. By completing this assignment, students will gain practical experience in handling data within relational databases, focusing on a database that records information about students and their courses.

Installation Instructions
Before you begin, ensure that you have either SQLite3 or SQLAlchemy installed in your Python environment. These tools are necessary for creating and interacting with your local database.

SQLite3 Installation
sh
Copy code
# Install SQLite3 on Ubuntu
sudo apt-get update
sudo apt-get install sqlite3
SQLAlchemy Installation
sh
Copy code
# Install SQLAlchemy using pip
pip install SQLAlchemy
Database Setup
The assignment involves working with a database named students.db, which comprises two main tables: students and courses.

Table Creation
Students Table: This table includes details such as student_id, name, major, gpa, and enrollment_date.
Courses Table: This table records the courses taken by students, including columns for course_id, course_name, student_id, and grade.
Scripts for creating these tables are provided in the assignment details.

Assignment Tasks
The tasks are divided into three categories, focusing on different aspects of SQL:

Q1: Simple SELECT Queries
Retrieve all records from the students table.
Filter the records to find students majoring in "Computer Science".
List all unique majors in descending order.
Find students with an 'e' in their names and sort them by GPA.
Q2: Joins
Count the total number of unique courses.
Identify Computer Science students enrolled in the "Python programming" course.
Select students who have earned grades higher than "C".
Q3: Aggregate Functions, Numerical Logic, and Grouping
Calculate the average GPA of all students.
Determine the student with the highest and lowest GPA.
Filter students with a GPA greater than 3.6 in specific majors.
Group students by major and calculate the average GPA for each.
