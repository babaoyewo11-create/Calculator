Simple Java Calculator

A console-based calculator application written in Java. This lightweight program prompts the user for two numbers and allows them to choose from basic arithmetic operations to calculate a result.

Features
 Interactive Menu: A simple command-line interface that guides the user through the process.
 Basic Arithmetic: Supports Addition, Subtraction, Multiplication, and Division.
 Decimal Support: Uses the double data type to calculate and display floating-point numbers accurately.
 Safe Division: Includes basic error handling to prevent program crashes when a user attempts to divide by zero.

Prerequisites

To compile and run this program, you will need:
 The Java Development Kit (JDK) installed on your machine.

How to Run
Open your terminal or command prompt.
Navigate to the parent directory that contains the day3 package folder.
Compile the Java file using the following command:
   ``bash
   javac day3/Calculator.java
   `
Run the compiled program:
   `bash
   java day3.Calculator
   `

Example Usage

When you run the program, the console will walk you through the calculation:

`text
Enter the first number
12.5
Enter the second number
4
Choose an operation
Addition
Subtraction
Multiplication
Division
3
3
Result: 50.0
``

(Note: The program is currently designed to echo your menu choice back to the console before displaying the final result).
