# Gradebook-student-management-system
Project Overview:

The student management system is one that system that manages student academic information, makes calculations and displays student information formally. It is a application that has been developed via python programming. This system allows users to add, remove, sort, store grades and calculate averages. The project exercises the use of classes, methods, objects and functions.

Set up instructions:

Application like PyCharm installed on pc
Open a command prompt
Locate the folder containing the project
Run the code using python main.py
Run comprehensive tests on the code

Features list:

Adds student
Adds students grades for specific subjects
Calculates students average
Displays the details of students
Removing students from Gradebook
Displaying all students and their details
Sort students by average using bubble sort
Sorting students by name
Sorting students based on subjects
Main menu

Class Architecture

Student class-contains name and grade attributes and had the add_grade method, calculate_average method and print_details methods.
Gradebook class-Manages students objects. It contains the following methods:Add_student, search_student, remove_student, display_student, sort_by_average,sort_by_subject and sort_by_name.

Example input/output

<img width="416" height="509" alt="image" src="https://github.com/user-attachments/assets/606d602b-d158-4d85-92f4-6263fd98e2cd" />

Assumptions and limitations

Assumptions:

Grades range from 0 to 100
Student names are all unique
Students subjects all have grades

Limitations:

students with same names or duplicates may cause errors

Data or information is stored temporarily

Testing Summary

<img width="543" height="218" alt="image" src="https://github.com/user-attachments/assets/5b2446ea-9770-4ce8-8fb6-b530a9c0b655" />

Known issues:

Duplicate student names cause errors- using unique name 

Empty grades corrupt averages-empty grades return a value of 0

References:

W3Schools. Python Classes and Objects. https://www.w3schools.com/python/python_classes.asp



 
