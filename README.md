# Basic Calculator

A simple calculator implemented in C.

## Functions Documentation

### int main()

**Purpose:**
- This is the main function that runs when the program starts. It displays a menu to the user, takes user input for the desired operation, and calls the corresponding function.

**Parameters:**
- None

**Returns:**
- An integer (0) to indicate successful completion of the program.

### void add()

**Purpose:**
- To add two numbers entered by the user and print the result.

**Parameters:**
- None (takes user input directly within the function).

**Functionality:**
- Prompts the user to enter two numbers.
- Reads the numbers using `scanf`.
- Adds the numbers and stores the result.
- Prints the result with two decimal places.

### void subtract()

**Purpose:**
- To subtract the second number from the first number entered by the user and print the result.

**Parameters:**
- None (takes user input directly within the function).

**Functionality:**
- Prompts the user to enter two numbers.
- Reads the numbers using `scanf`.
- Subtracts the second number from the first and stores the result.
- Prints the result with two decimal places.

### void multiply()

**Purpose:**
- To multiply two numbers entered by the user and print the result.

**Parameters:**
- None (takes user input directly within the function).

**Functionality:**
- Prompts the user to enter two numbers.
- Reads the numbers using `scanf`.
- Multiplies the numbers and stores the result.
- Prints the result with two decimal places.

### void divide()

**Purpose:**
- To divide the first number by the second number entered by the user and print the result.

**Parameters:**
- None (takes user input directly within the function).

**Functionality:**
- Prompts the user to enter two numbers.
- Reads the numbers using `scanf`.
- Checks if the second number is zero (to avoid division by zero).
  - If not zero, divides the first number by the second and stores the result.
  - Prints the result with two decimal places.
  - If zero, prints an error message.
