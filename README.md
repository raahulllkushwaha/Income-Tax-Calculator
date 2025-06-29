# Income Tax Calculator

A simple Java program that calculates income tax based on predefined tax brackets.

## Description

This program calculates income tax using a simplified tax bracket system:
- Income below ₹5,00,000: No tax (0%)
- Income ₹5,00,000 to ₹9,99,999: 20% tax
- Income ₹10,00,000 and above: 30% tax

## Features

- Interactive console input for income amount
- Automatic tax calculation based on income brackets
- Clean output displaying the calculated tax amount

## Requirements

- Java Development Kit (JDK) 8 or higher
- Any Java IDE or command line interface

## How to Run

### Using Command Line:

1. **Compile the program:**
   ```bash
   javac IncomeTaxCalc.java
   ```

2. **Run the program:**
   ```bash
   java IncomeTaxCalc
   ```

### Using an IDE:
1. Copy the code into your Java IDE
2. Run the `IncomeTaxCalc` class

## Usage

1. Run the program
2. Enter your annual income when prompted
3. The program will calculate and display your tax amount

### Example:

```
Enter the income: 
750000
Your tax is: 150000
```

## Tax Calculation Logic

The program uses the following tax brackets:

| Income Range | Tax Rate |
|--------------|----------|
| < ₹5,00,000 | 0% |
| ₹5,00,000 - ₹9,99,999 | 20% |
| ≥ ₹10,00,000 | 30% |

## Code Structure

- `main()` method handles user input and output
- Tax calculation is performed using if-else conditional statements
- Scanner class is used for reading user input
- Results are cast to integer values for whole number output

## Note

This is a simplified tax calculator for educational purposes. Actual tax calculations may involve more complex rules, deductions, and brackets depending on your country's tax laws.