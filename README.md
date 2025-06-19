# python
INTRODUCTION TO PYTHON AND HISTORY OF PYTHON
FUNCTIONS & MODULES
FINDING OUT ERROR AND EXPLAIN THE ERROE
WRITING CORRECTED CODE


 What is Python?
High-level, interpreted programming language

Easy to learn and use

Emphasizes code readability

Open-source and cross-platform

“Simple is better than complex.” – The Zen of Python



History of Python
Created by: Guido van Rossum

Started: Late 1980s, officially released in 1991

Named after: Monty Python’s Flying Circus (not the snake 🐍)

Versions:

Python 2 (2000) – Now deprecated

Python 3 (2008–present) – Actively developed




Why Use Python?
Clean and simple syntax

Large standard library

Huge community support

Used in:

Web development

Data Science

AI/ML

Automation

Game development






Python Functions - Introduction
A function is a block of reusable code

Helps make programs modular and readable

Syntax:

def function_name(parameters):
    # code block
    return value
⚙️ Slide 6: Function Example
python
Copy
Edit
def greet(name):
    return "Hello, " + name

print(greet("Alice"))
✅ Output: Hello, Alice

def defines the function

name is the parameter

return sends back the result




Types of Functions
Built-in Functions: print(), len(), type(), etc.

User-defined Functions: Created using def

Lambda Functions: Anonymous, single-expression functions

square = lambda x: x * x
print(square(5))  # Output: 25


Python Modules - Introduction
A module is a file containing Python code (functions, classes, variables)

Helps in code organization and reuse


Using Modules
Importing built-in module:

import math
print(math.sqrt(25))  # Output: 5.0
Creating and importing your own module:


# In file: mymodule.py
def welcome():
    print("Welcome to Python!")

# In main file
import mymodule
mymodule.welcome()


Built-in vs. External Modules
Built-in: math, random, datetime, os

External: numpy, pandas, requests
(Install with pip install package_name)



 Summary
Python is easy to learn and widely used

Functions simplify code reuse and structure

Modules organize functions into reusable files

