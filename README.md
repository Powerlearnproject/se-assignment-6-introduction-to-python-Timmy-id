[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15317067&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

      - Python is a programming language and some of its key features are:
         - it is free and open source
         - it is easy to code compared to other programming languages
         - it supports object-oriented programming
      - Some of the use cases of Python are:
         - scripting and automation
         - Data analysis 
         - Data processing
         - Web development
Source: [https://www.freecodecamp.org/news/what-is-python-best-for/](https://www.freecodecamp.org/news/what-is-python-best-for/)

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

      - To install python:
         - Download the installer from the official Python website
         - Install the package after downloading by following the prompts
         - To verify the installation, on windows powershell, use ```python --version```. If it brings the version of Python installed, then the installation was successful.
      - To setup a virtual environment:
         - install the virtual environment package, venv using ```pip install virtualenv```
         - to use the virtual environment, use ```py -m venv name_of_virtual_environment```
         - then you activate the virtual environment using ```name_of_virtual_environment/Scripts/activate```
         - (NB: The steps are for a Windows 10 computer)
Source: [https://www.freecodecamp.org/news/how-to-setup-virtual-environments-in-python/](https://www.freecodecamp.org/news/how-to-setup-virtual-environments-in-python/)

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

      - ```print("Hello, World!)```
      - The print() function executes the code in the paranthesis and outputs it in the console.

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

      - The basic data types in Python are:
         - int
         - float
         - str
         - list
         - dict
      - 
         ```
            stringVariable = "Oluwatimilehin"
            integerVariable = 20
            listVariable = [1, 2, "fish"]
            floatVariable = 3.45
            dictionaryVariable = { "name": "Timmy", "age": 20 }

            print(stringVariable)
            print(integerVariable)
            print(listVariable)
            print(floatVariable)
            print(dictionaryVariable)
         ```

5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

      - Conditional statements in Python can be specified using if, else and elif
      - Loops can be specified using for or while
         - Conditional statements
         ```
            age = 21
            if age > 19:
               print("User is not a teenager")
            else:
               print("User is a teenage")
         ``` 
         - Loops
         ```
            myName = "Timmy"
            for i in myName:
               print(i)
         ```

6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

      - A function is a block of code that performs a particular task when called. They are useful because it makes codes reusable without having to write the codes from scratch.
      - 
      ```
         def add(a, b):
            return a + b
         
         add(2, 5)
      ```

7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

      - Lists are used for storing data linearly while datas are stored in dictionaries in key-value pair.
      - 
      ```myList = [1, 3, 5, 7]
         my_dictionary = { "food": "rice", "quantity": 2 }

         print(myList[0])
         print(my_dictionary["name"])

      ``` 

8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

      - Exception handling is a coding method in Python that allows for handling exceptional cases that will originally cause an error or break our code.
      - 
      ```
         try:
            print(myName)
         except:
            print("myName is not defined")
         finally:
            print("I am always going to appear")
      ```

9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

      - A module is a single file that contain Python codes while a package is a collection of modules
      - To import and use a module,
         ```
            import math

            print(math.add(3, 5))
         ```
Source: [https://www.shiksha.com/online-courses/articles/difference-between-module-and-package-in-python/#:~:text=In%20Python%2C%20both%20modules%20and,explore%20the%20differences%20between%20them.](https://www.shiksha.com/online-courses/articles/difference-between-module-and-package-in-python/#:~:text=In%20Python%2C%20both%20modules%20and,explore%20the%20differences%20between%20them.)

10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

      - To read from a file in Python, use:
         ```
            f = open("myFile.txt")
            print(f.read())
         ```
      - To write a list of strings to a file:
         ```
            fruits = ["mango", "cashew", "banana"]

            with open("fruits.txt", "w") as f:
               f.write("\n".join(fruits))
         ```
Source: [https://sentry.io/answers/write-a-list-to-a-file-in-python-with-each-item-on-a-new-line/](https://sentry.io/answers/write-a-list-to-a-file-in-python-with-each-item-on-a-new-line/)

# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


