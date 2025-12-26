Perfect! Functions & Modules

1. What is a Function?

A function is a block of reusable code designed to perform a specific task.
Functions help make programs organized, readable, and reusable, reducing repetition.

Basic Example:

def greet():
    print("Hello, welcome to Python!")

Explanation:

def keyword is used to define a function.

greet is the function name.

The code inside the function runs only when the function is called.


Calling a Function:

greet()

Output:

Hello, welcome to Python!

Why it matters:
Instead of writing the same print statement multiple times, you just call greet() whenever needed.


2. Functions with Parameters

Functions can take input values, called parameters, to make them more flexible.

def greet_person(name):
    print(f"Hello, {name}! Welcome to Python.")

Calling the Function:

greet_person("Gerrad")

Output:

Hello, Gerrad! Welcome to Python.

Explanation:

name is a parameter.

You pass a value (called an argument) when calling the function.

This makes your function reusable for different inputs.



3. Functions with Return Values

Functions can also return a result instead of just printing it.

def add(a, b):
    return a + b

Calling the Function:

result = add(5, 7)
print("Sum:", result)

Output:

Sum: 12

Why it matters:
Returning a value allows the function to be used in calculations or further processing, making your code more modular.


4. Modules: Organizing Functions

A module is a file containing Python functions, variables, and classes.
Modules allow you to organize code and reuse it across different programs.

Example: Creating a module

1. Save functions in a file named math_utils.py:



def add(a, b):
    return a + b

def subtract(a, b):
    return a - b

2. Use it in another file:



import math_utils

print(math_utils.add(10, 5))
print(math_utils.subtract(10, 5))

Output:

15
5

Why it matters:
Modules help you structure large projects, avoid repetition, and make your code maintainable.


5. Key Takeaways

Functions: Reusable blocks of code that perform a task.

Parameters: Allow functions to accept input and become flexible.

Return Values: Allow functions to output results for further use.

Modules: Organize functions and variables into reusable files for cleaner projects.
