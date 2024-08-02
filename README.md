# calculator_osslab
Overview
The C++ Calculator project is a command-line calculator application implemented in C++. It provides basic arithmetic operations including addition, subtraction, multiplication, and division. The calculator is designed to handle integer inputs and operations, and offers a simple user interface for performing calculations.

Project Structure
The repository is organized into the following main components:

main.cpp: The primary source file containing the main function and user interface logic.
calculator.cpp: Contains the implementation of arithmetic operations and related functions.
calculator.h: Header file declaring the functions and classes used in calculator.cpp.
Files
main.cpp

Description: This file contains the entry point of the program and handles user input and output.
Key Functions:
int main(): Displays a menu, processes user input, and invokes functions from calculator.cpp based on user choices.
calculator.cpp

Description: Implements the core arithmetic operations.
Key Functions:
int add(int a, int b): Returns the sum of a and b.
int subtract(int a, int b): Returns the difference between a and b.
int multiply(int a, int b): Returns the product of a and b.
float divide(int a, int b): Returns the quotient of a divided by b. Handles division by zero.
calculator.h

Description: Declares functions for arithmetic operations used in calculator.cpp.
Key Contents:
Function prototypes for add(), subtract(), multiply(), and divide().