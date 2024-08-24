Name:Pranita Dnyaneshwar Tupe
Company:CODETECH IT SOLUTIONS
ID:CT08DS6343
Domain:Python Programming
Duration:August to September 2024
Mentor:Muzammil Ahmed

Overview of the project

Here's an overview of a simple calculator Python program project:

Project: Simple Calculator

Description: A command-line calculator program that performs basic arithmetic operations.

Features:

1. Basic Operations: Addition, Subtraction, Multiplication, Division
2. User Input: Get user input for numbers and operation
3. Error Handling: Handle invalid inputs and division by zero
4. Results: Display the result of the operation

Python Code Structure:

1. Functions: Define functions for each operation (add, subtract, multiply, divide)
2. Main Program: Get user input, call corresponding function, and display result
3. Error Handling: Use try-except blocks to handle errors

Example Code:

       # Simple Calculator Program

num1 = float(input("Enter first number: "))
operation = input("Enter operation (+, -, *, /): ")
num2 = float(input("Enter second number: "))

if operation == '+':
    result = num1 + num2
elif operation == '-':
    result = num1 - num2
elif operation == '*':
    result = num1 * num2
elif operation == '/':
    if num2 != 0:
        result = num1 / num2
    else:
        result = "Error! Division by zero."
else:
    result = "Invalid operation."

print(f"The result is: {result}")

Output:
C:\Users\Pranita\PycharmProjects\pythonProject7\.venv\Scripts\python.exe C:\Users\Pranita\PycharmProjects\pythonProject7\main.py 
Enter first number: 78905
Enter operation (+, -, *, /): /
Enter second number: 567849
The result is: 0.1389541938085653

Process finished with exit code 0


Project Goals:

1. Practice Python basics: Variables, data types, functions, control structures
2. Understand error handling: Try-except blocks, error messages
3. Improve problem-solving skills: Break down problem into smaller parts, write reusable code

This project is a great starting point for beginners to practice Python programming and build a simple calculator.
