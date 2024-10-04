# Recursion-Implementation
This Java program calculates partial derivatives of mathematical expressions, parses input formulas, and evaluates them. It supports basic operations like addition, multiplication, and exponentiation, using stacks to handle constants and variables. The result is printed after evaluating the differentiated expression.




Partial Derivative Calculator
This Java program calculates partial derivatives of mathematical expressions with respect to given variables and evaluates them using provided values. It supports basic arithmetic operations like addition (+), multiplication (*), and exponentiation (^).

Features
Input Parsing: Reads a mathematical expression and variables for differentiation.
Partial Differentiation: Calculates the derivative of the expression with respect to each variable.
Expression Evaluation: Evaluates the differentiated expression by substituting the provided values for variables.
Operators Supported: Addition (+), multiplication (*), and exponentiation (^).
Usage
Input the formula as a string.
Provide the variables for differentiation.
Enter the variable values for evaluation.
The program outputs the result of the evaluated differentiated expression.
Example

Input Formula: (x + y) * z
Variables for differentiation: x y
Values for x, y, z: 2 3 4
Output:


Result: [calculated result]
How It Works
Parsing: The formula is tokenized, and stacks are used to manage operators and operands.
Differentiation: The program differentiates constants and variables, handling operations like multiplication and addition.
Evaluation: After differentiation, the program evaluates the expression using a map of variable values.
Requirements
Java 8 or higher



Created By:
Usman Haider - Designer & Developer
