# Experiment 01: Python Fundamentals for Exploratory Data Analysis

## Department: Electronics & Telecommunication (EnTC)

 ## Lab Session: 01

<mark> Topic: Syntax, Data Types, I/O Streams, and Conditional Logic </mark>
1. Overview

This laboratory session serves as the foundational entry point for Exploratory Data Analysis (EDA). The experiment systematically explores the Python execution model, moving from basic syntax verification to constructing interactive tools like a geometric estimator and a functional arithmetic calculator.

2. Learning Objectives (Aim)

To develop a working proficiency in Python by implementing the following concepts:

    Syntax & Semantics: Understanding indentation, comments, and multi-line execution.

    Memory Management: Utilizing dynamic variables, case sensitivity, and multiple assignments.

    Data Type Introspection: analyzing standard types (int, float, str, complex).

    Advanced I/O: Implementing complex input parsing using map() and split().

    Algorithmic Logic: Designing control flow using conditional (if-else) statements.

3. Experiment Tasks & Implementation

The following tasks were executed sequentially within the Experiment_1.ipynb notebook:
Task 1: Environment Setup & Syntax Verification

    Objective: Verify the standard output stream (stdout) and Python interpreter health.

    Execution:

        Implemented the classic "Hello World" verification.

        Demonstrated Multi-statement Execution using semi-colons (;) to run multiple commands on a single physical line.

        Code Snippet: print("Hello"); print("World")

Task 2: Arithmetic Operations

    Objective: Validate the mathematical logic unit of Python.

    Execution:

        Performed fundamental operations: Addition (+), Subtraction (-), Multiplication (*), and Division (/).

        Verified the Modulus operator (%) for remainder calculation.

Task 3: Variables & Data Structures

    Objective: Explore how Python handles memory and data types without explicit declarations.

    Execution:

        Dynamic Typing: Assigned integers, strings, and booleans to variables.

        Case Sensitivity: Verified that variable a and A are stored in separate memory locations.

        Unpacking: Assigned values to multiple variables in one line (x, y, z = "Orange", "Banana", "Cherry").

        Type Checking: Used type() to identify complex numbers (3+2j), lists, and floats.

Task 4: Input/Output Handling

    Objective: Create interactive scripts that accept dynamic user data.

    Execution:

        Basic Input: Captured user name and age using input().

        Advanced Parsing: Implemented a one-line input parser for a list of integers (e.g., Marks) using list(map(int, input().split())). This demonstrates vector-style data ingestion common in Data Science.

Task 5: Functional Applications

    Sub-Task A: Geometric Calculator

        Logic: Calculates the Area of a Circle given user-defined radius.

        Formula: Area=π×r2 (using π≈3.14).

    Sub-Task B: Simple Calculator (Final Project)

        Logic: A decision-based program that asks for two integers and an operator.

        Control Flow: Uses sequential if statements to detect the operator (+, -, x, /) and execute the corresponding math logic.

        Error Handling: Includes a fallback message ("no output") if the user provides unrecognized input.

4. Software & Tools Used

    Language: Python 3.10+

    Interactive Environment: Google Colab / Jupyter Notebook

    Core Libraries: Built-in Standard Library (No external pip installs required).

5. Conclusion

This experiment successfully demonstrated the versatility of Python for engineering applications. By progressing from simple output commands to a fully functional calculator with conditional logic, we established the core prerequisites for advanced data manipulation and algorithm design required for the EDA course.

Submitted by:
   Name: Bedang das 

   PRN : 25070123031

   Date: 13/01/2026
