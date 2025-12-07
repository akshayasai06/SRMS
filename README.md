# Student Record Management System (SRMS)

This project is a simple C program used to manage basic student information.  
It allows storing and viewing student details using a CSV file.

## Files Included
- *srms.c* – Main program file  
- *students.csv* – Data file (initially empty)

## How to Run
Compile the program using GCC or any C compiler:gcc srms.c -o srms ./srms

## About the Project
The program stores student details such as:
- Name  
- Roll Number  
- Course  
- Year  

The data is saved into *students.csv*, which gets updated whenever new records are added.

## Notes
- students.csv is empty initially because no records have been added yet.
- The program will create/update this file as data is entered.
