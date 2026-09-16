# Student Management System – Python

This project is a **Python-based Student Management System** designed to practice and demonstrate important Python programming concepts using real-world student data.

The program stores student information such as **roll number, name, age, course, and marks** using a list of dictionaries. It performs different operations including displaying student records, searching students, calculating marks, identifying the topper, counting students by course, and managing student information using Object-Oriented Programming (OOP).

# Features

* Display complete details of all students.
* Display only the names of students.
* Calculate the total marks obtained by all students.
* Calculate the average marks of the class.
* Determine whether students have passed or failed based on passing marks of 70.
* Assign grades according to students' marks.
* Search for a student using their roll number.
* Search for a student by name with case-insensitive matching.
* Find the topper of the class based on maximum marks.
* Count the number of students enrolled in each course.
* Remove duplicate courses using Python sets.
* Create a `Student` class using Object-Oriented Programming.
* Create student objects and display their information.
* Implement a menu-driven Student Management System.

# Concepts Practiced

This project covers several fundamental and intermediate Python concepts:

* Lists
* Dictionaries
* Sets
* Loops
* Conditional Statements
* Functions
* User Input
* String Methods
* Case-Insensitive Searching
* `return` Statements
* `len()` and `sum()` concepts
* Dictionary Traversal
* Counting with Dictionaries
* Object-Oriented Programming
* Classes and Objects
* Constructors (`__init__`)
* Instance Methods
* Menu-Driven Programs

# Student Data Structure

Each student is represented using a dictionary containing:

```python
{
    "roll": 101,
    "name": "Rahul",
    "age": 20,
    "course": "Python",
    "marks": 85
}
```

Multiple student dictionaries are stored inside a list, making it possible to process the complete class data using loops.

# Grading System

The project also demonstrates conditional logic for assigning grades based on marks:

| Marks    | Grade |
| -------- | ----- |
| 90+      | A     |
| 75+      | B     |
| 60+      | C     |
| Below 60 | D     |

# Object-Oriented Programming

The project includes a `Student` class that represents individual students as objects. The class contains student attributes such as name, age, roll number, course, and marks.

A `display()` method is used to print the details of each student object.

# Menu-Driven System

The final section introduces a menu-driven approach where the user can select different operations such as:

1. Display Students
2. Search Student
3. Find Topper
4. Calculate Average
5. Exit

This helps demonstrate how Python programs can be structured into an interactive application.

# Learning Objective

The main objective of this project is to strengthen Python fundamentals by combining **data structures, functions, loops, conditions, searching, calculations, and OOP** into one practical project.

This project represents a step toward building larger Python applications such as database-driven student management systems and other real-world management applications.

# Future Improvements

Possible improvements for this project include:

* Add new students through user input.
* Update existing student information.
* Delete student records.
* Add proper menu options for every operation.
* Store student data in a file or database.
* Add exception handling for invalid input.
* Improve the grading function.
* Add sorting by marks, name, or roll number.
* Convert the project into a complete GUI or web application.

# Technologies Used

* **Python 3**
* Core Python Data Structures
* Object-Oriented Programming (OOP)

#Conclusion

This Student Management System is a practical Python project created to apply fundamental programming concepts in a single application. It demonstrates how Python can be used to organize, process, search, and manage structured student information while providing hands-on experience with both procedural programming and Object-Oriented Programming.
