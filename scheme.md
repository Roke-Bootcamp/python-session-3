# Python Functions and Modules - Roke Bootcamp

## Introduction
Welcome to the "Python Functions and Modules" module of the Roke Bootcamp! Functions and modules are essential building blocks of Python programming, enabling developers to organise code into reusable and manageable components. In this module, we'll delve into the world of functions and modules in Python, exploring how to define, call, and utilise functions, as well as how to organise code into modular and reusable modules.

## Learning Objectives
By the end of this module, you will:
- Understand the concept of functions and their role in Python programming.
- Learn how to define and call functions, pass arguments, and return values.
- Gain proficiency in writing modular and reusable code by creating and importing Python modules.
- Explore advanced topics such as function parameters, variable scope, and function decorators.

## Detailed Scheme of Work

### Hour 1: Understanding Functions

#### Welcome and Overview (5 minutes)
- Introduction to the session and its objectives.
- Brief discussion on the importance of functions in programming.

#### Introduction to Functions (10 minutes)
- **Explanation:** What are functions and why they are used.
- **Examples:** Basic syntax of function definition and function call.

#### Defining Functions (20 minutes)
- **Demonstration:** 
  ```python
  def greet(name):
      print("Hello, " + name)
  greet("Alice")

## Hands-on Activity: Students define and call their own simple functions.

### Function Parameters (15 minutes)
- **Explanation:** Passing parameters to functions.
- **Examples:**
  ```python
  def add(x, y):
      return x + y
  result = add(3, 5)

## Hands-on Activity: Students practice defining functions with parameters.

### Return Values (10 minutes)
- **Explanation:** Returning values from functions.
- **Examples:**
  ```python
  def square(x):
      return x * x
  result = square(4)

## Hands-on Activity: Students write functions that return values.

### Break (10 minutes)

## Hour 2: Python Modules and Advanced Function Topics

### Introduction to Modules (10 minutes)
- **Explanation:** What are modules and why they are used.
- **Examples:** Importing built-in and custom modules.

### Creating and Importing Modules (15 minutes)
- **Demonstration:**
  - Creating a simple Python module.
  - Importing the module into another Python script.
- **Hands-on Activity:** Students create their own Python modules and import them.

### Function Parameters and Variable Scope (20 minutes)
- **Explanation:** Understanding function parameters and variable scope.
- **Examples:**
  ```python
  def example_func(x):
      y = 10
      return x + y

## Hands-on Activity: Students explore function parameters and variable scope.

### Function Decorators (10 minutes)
- **Explanation:** Introduction to function decorators and their use cases.
- **Examples:**
  ```python
  def my_decorator(func):
      def wrapper():
          print("Something is happening before the function is called.")
          func()
          print("Something is happening after the function is called.")
      return wrapper
  
  @my_decorator
  def say_hello():
      print("Hello!")

## Hands-on Activity: Students experiment with creating and using function decorators.

### Summary and Q&A (5 minutes)
- Recap of what was learned in the session.
- Open floor for questions and clarifications.

## Materials Needed
- Computers with Python installed.
- A simple text editor or Python IDE (IDLE, PyCharm, VS Code).
- Handouts or slides with key points and examples.

## Activities
- Hands-on coding exercises.
- Short quizzes or interactive questions during the session to keep students engaged.

## Additional Notes
- Encourage students to ask questions throughout the session.
- Provide additional resources for further reading and practice, such as online tutorials and documentation.
- Follow up with students to ensure they have successfully understood functions and modules in Python.


