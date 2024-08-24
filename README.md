# Unconventional Arithmetic Calculator

## Overview

Welcome to the **Unconventional Arithmetic Calculator**! This calculator allows you to perform arithmetic operations (addition, subtraction, multiplication, and division) on an initial value with continuous input, offering a dynamic way to explore numbers.

## Features

- **Addition**: Adds the inputted value to the initial value.
- **Subtraction**: Subtracts the inputted value from the initial value.
- **Multiplication**: Multiplies the initial value by the inputted value.
- **Division**: Divides the initial value by the inputted value.

## Usage

1. Initialize the calculator with a starting value.
2. Input a value to perform an operation.
3. The calculator will apply the operation using the initial value and the inputted value.
4. Continue inputting values to see how the result evolves.

### Example

```python
# Initialize the calculator
calculator = UnconventionalArithmeticCalculator(10)

# Add 5 to the initial value
calculator.add(5)  # Result: 15

# Subtract 3 from the result
calculator.subtract(3)  # Result: 12

# Multiply the result by 2
calculator.multiply(2)  # Result: 24

# Divide the result by 4
calculator.divide(4)  # Result: 6
