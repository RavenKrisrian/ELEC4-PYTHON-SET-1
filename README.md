# ELEC 4 - Python Programming | Set 1

**Name:** Raven Kristian Abarintos  
**Section:** IV-BSIT C  
**Course:** ELEC 4 - Python Programming  

## Overview

This repository contains the four activities for Python Programming Set 1. Each activity practices fundamental Python concepts, including functions, modules, collections, input validation, and exception handling.

## Activities

### P1 - Student Grade Calculator

A menu-driven program that accepts student grades and calculates the average, highest grade, and lowest grade. It also determines whether the student passed or failed based on the passing grade.

**Concepts used:**
- Functions
- Lists
- Loops and menu selection
- Input validation
- Average, highest, and lowest values
- Pass/fail condition

How to run:


powershell
py p1_grade_calculator.py
<img width="1359" height="759" alt="image" src="https://github.com/user-attachments/assets/c61b8d1a-36a0-4ac2-9471-4359b7bd5490" />

---

### P2 - Custom Module: `student_utils`

This activity demonstrates how to create and use a custom Python module. Reusable functions are placed in `student_utils.py` and imported into the main program. The activity also demonstrates different import styles and the use of a built-in Python module.

**Concepts used:**
- Creating custom modules
- Importing functions
- Reusable code
- Built-in modules
- Functions for grade calculations and status

**How to run:**

powershell
py p2_main.py



---

### P3 - Student Record Manager

A simple program for managing student names. Users can add, remove, search, and display names. The program avoids duplicate names and provides search functionality.

**Concepts used:**
- Lists and sets
- Adding and removing records
- Searching for names
- Preventing duplicate entries
- Sorting and displaying records

**How to run:**

powershell
py p3_record_manager.py






### P4 - Safe Menu Program (Exception Handling)

This program demonstrates how Python handles errors through exception handling. It includes a menu, division operation, and file-reading operation. It handles invalid inputs, division by zero, and missing files without abruptly terminating the program.

**Concepts used:**
- `try`, `except`, `else`, and `finally`
- `ValueError`
- `ZeroDivisionError`
- `FileNotFoundError`
- Input validation
- Safe program execution

**How to run:**

powershell
py p4_exceptions.py
<img width="1366" height="768" alt="exceptions" src="https://github.com/user-attachments/assets/85dd376e-b474-47e6-a115-2cb9c654b07c" />


## Folder Structure

text
ELEC4-PYTHON-SET-1/
│
├── p1/
│   └── p1_grade_calculator.py
│
├── p2/
│   ├── student_utils.py
│   └── p2_main.py
│
├── p3/
│   └── p3_record_manager.py
│
├── p4/
│   └── p4_exceptions.py
│
├── .gitignore
└── README.md



