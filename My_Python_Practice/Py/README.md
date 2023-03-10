# Weekly Progress Report - March 3-12, 2023

## Overview

This week's progress on my Python learning journey has been slow due to personal obligations, but I am committed to completing Section 10 of Jose Portilla's "Zero to Hero in Python" course, which focuses on exception handling.

## Section 10 - Error Handling

### Description

Error handling is a crucial part of any programming language, and Python is no exception. The goal of error handling is to anticipate and handle errors that may occur during the execution of a program. In Python, errors are referred to as exceptions, and they can be handled using try-except blocks.

### Example

Here's a simple example of using a try-except block to handle a potential error in Python:

```python
try:
    # some code that may raise an exception
    age = int(input("Enter your age: "))
except ValueError:
    # handle the exception if it occurs
    print("Invalid input. Please enter a valid integer for your age.")  
    ```
    

    
    This code prompts the user to enter their age as an integer, but if they enter a non-integer value (e.g. "abc"), a ValueError exception will be raised. The try-except block catches the exception and prints a message to the user.
## Tools Used

I am using a combination of Jupyter Notebook and Visual Studio Code to complete the course exercises and practice problems. Both tools are excellent for Python development and offer a range of features to support learning and development.

