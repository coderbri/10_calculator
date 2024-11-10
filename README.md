# 10 Calculator

## Overview

The **Calculator Program** is a Python application that performs basic arithmetic operations and demonstrates key concepts like storing functions as variable values. It was built as part of Day 10 in Dr. Angela Yu's **100 Days of Code: The Complete Python Pro Bootcamp**, focusing on dictionary usage and function references.

## Key Concepts

1. **Function References**: Functions for addition, subtraction, multiplication, and division are stored as values in a dictionary. This allows the program to dynamically select the correct operation based on user input.

2. **Dictionary Operations**: The program uses a dictionary where keys represent operators (`+`, `-`, `*`, `/`) and values are the corresponding functions. This enables a clean and flexible way to call operations.

3. **Loop Control for Continuous Calculation**: Users can choose to continue calculations using the previous result or start fresh, providing a seamless user experience.


## Functionality

1. **Basic Calculations**: The program performs addition, subtraction, multiplication, and division based on user input.

2. **Continuous Operation**: Users can keep calculating with the last result or start over at any time.

3. **Output Clearing**: Clears previous calculations when the user decides to start fresh.

## Program Flow

1. **User Input**: The program prompts for the first number, an operator, and the second number.

2. **Operation Execution**: It performs the calculation using the selected operator from the dictionary and displays the result.

3. **Continuation Option**: Users can choose to continue with the current result or reset the calculator to start over.


## Example Code Snippet

```python
operations = {
    "+": add,
    "-": subtract,
    "*": multiply,
    "/": divide
}

# Execute operation by accessing function via dictionary
answer = operations[operation_symbol](num1, num2)
print(f"{num1} {operation_symbol} {num2} = {answer}")
```

## Sample Output
```
What's the first number?: 5
Pick an operation: *
What's the next number?: 4
5 * 4 = 20
Type 'y' to continue calculating with answer 20, or type 'n' to start over: y
Pick an operation: +
What's the next number?: 10
20 + 10 = 30
```


---
<section align="center">
  <code>coderBri © 2024</code>
</section>