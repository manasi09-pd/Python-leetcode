# 30 Days of Python — Learning Series

## Day 1: Introduction, Environment Setup, and Python Basics

This repository documents a structured Python learning journey focused on building strong fundamentals through hands-on practice.

---

## Environment Setup

### Python Installation link
https://www.python.org/downloads/

### Verify Python Installation

~~~bash
python --version
~~~

If a Python version (3.6 or above) is displayed, Python is installed successfully.

---

## Python Interactive Shell

Start the Python interactive shell:

~~~bash
python
~~~

Exit the shell:

~~~python
exit()
~~~

---

## Basic Python Operations

~~~python
2 + 3     # Addition
3 - 2     # Subtraction
3 * 2     # Multiplication
3 / 2     # Division
3 ** 2    # Exponentiation
3 % 2     # Modulus
3 // 2    # Floor division
~~~

---

## Comments in Python

### Single-line Comment

~~~python
# This is a single-line comment
~~~

### Multi-line Comment

~~~python
"""
This is a multi-line comment.
Used for documentation or notes.
"""
~~~

---

## Python Data Types Overview

| Data Type | Description |
|----------|-------------|
| int | Integer numbers |
| float | Decimal numbers |
| complex | Complex numbers |
| str | Text data |
| bool | Boolean values |
| list | Ordered, mutable collection |
| tuple | Ordered, immutable collection |
| set | Unordered collection of unique values |
| dict | Key-value pairs |

---

## Checking Data Types

~~~python
print(type(10))                 # int
print(type(3.14))               # float
print(type(1 + 3j))             # complex
print(type("Python"))           # str
print(type(True))               # bool
print(type([1, 2, 3]))          # list
print(type((1, 2, 3)))          # tuple
print(type({1, 2, 3}))          # set
print(type({"key": "value"}))   # dict
~~~

---

## Writing and Running a Python File

Python scripts are saved with a `.py` extension.

### Example File: `helloworld.py`

~~~python
# Day 1 - Python Basics

print(2 + 3)
print(3 * 2)
print(3 / 2)
print(type("Python"))
print(type([1, 2, 3]))
~~~

### Run the Script

~~~bash
python helloworld.py
~~~

---

## Exercises — Day 1

### Practice Tasks

| Task No | Description |
|--------|-------------|
| 1 | Check the Python version installed |
| 2 | Open the Python interactive shell |
| 3 | Perform arithmetic operations (+, -, *, /, %, **, //) |
| 4 | Write and print strings |
| 5 | Identify data types using `type()` |

### Example Practice

~~~python
print("I am learning Python")
print(type(9.8))
print(type(["Python", "Day 1"]))
~~~

---

## Summary

| Topic | Status |
|------|--------|
| Python installation | Completed |
| Interactive shell | Practiced |
| Arithmetic operations | Practiced |
| Comments | Covered |
| Core data types | Introduced |
| Python file execution | Completed |

Day 1 establishes the foundation required to continue learning Python effectively.

