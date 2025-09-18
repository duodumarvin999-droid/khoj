Web-Application-Assignment
Group Project Work (KODES)

Group Members
Pwabasia Benjamin Akwo - 01244281B
Mbiah Amos Adu - 01241847B
Kojo Amoako - 01243202B
Mohammed Abubakar - 01242229B
Duodu Marvin Kontoh - 01242945B
ABOUT PROJECT
This project is a basic calculator web application built using the Flask framework in Python. It provides a simple web interface where users can input two numbers, select an arithmetic operation (Addition, Subtraction, Multiplication, or Division), and get the result displayed on the same page.

Objectives
To build a working calculator accessible via a web browser.

To demonstrate Flask integration with HTML for interactive apps.

To handle basic error cases like invalid input or division by zero.

To practice Python web development concepts.

Backend Logic (in Python)
*Handles form submission (POST method).

*Performs operations in Python:

*Addition

*Subtraction

*Multiplication

*Division (with division by zero check)

Error Handling
Displays "Error: Division by zero" if denominator is 0.

Displays "Invalid input" for incorrect form inputs.

Workflow
User opens the application in a browser (http://127.0.0.1:5000).

User enters two numbers and selects an operation.

Flask receives the input (via POST) and computes the result.

The result is displayed on the same page.

If input is invalid or division by zero occurs, an error message is shown.

Example Usage
Input: 12 ÷ 4

Output: Result: 3.0

Input: 7 - 2

Output: Result: 5.0

Input: 10 ÷ 0

Output: Error: Division by zero

Strengths of the Project
*Simple and easy-to-use calculator.

*Fully implemented in Python + Flask.

*Demonstrates form handling and dynamic HTML rendering.

*Includes error handling for robustness.