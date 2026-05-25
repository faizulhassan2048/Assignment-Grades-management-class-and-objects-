# Teacher Grade Management System

A simple Python project built using Object-Oriented Programming (OOP) concepts. This project demonstrates how a Teacher class can store grades and calculate the average grade.

## Features

- Create Teacher objects
- Add multiple grades
- Calculate average grade
- Beginner-friendly OOP implementation

## Technologies Used

- Python
- Object-Oriented Programming (OOP)

## Project Structure

```text
Teacher-Grade-Management-System/
│
├── main.py
└── README.md
```

## Code Example

```python
class Teacher:
    def __init__(self, name):
        self.name = name
        self.grades = []

    def add_grade(self, grade):
        self.grades.append(grade)

    def get_average_grade(self):
        return sum(self.grades) / len(self.grades)

teacher1 = Teacher("Dr Nouman")

teacher1.add_grade(80)
teacher1.add_grade(90)
teacher1.add_grade(85)

print(teacher1.get_average_grade())
```

## Output

```text
85.0
```

## Learning Objectives

- Understanding Classes and Objects
- Working with Instance Variables
- Using Methods in Python
- Applying Basic OOP Concepts

## Author

Faiz Ul Hassan
