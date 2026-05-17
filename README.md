# Roman-To-Integer

A Python program that validates Roman numerals entered by the user and suggests corrections if the entered Roman numeral is incorrect.

## Overview

This project provides a comprehensive solution for validating Roman numeral inputs according to standard Roman numeral conventions. If a user enters an invalid Roman numeral, the program intelligently suggests the correct format.

## Features

- ✓ Validates Roman numeral input from users
- ✓ Detects invalid or malformed Roman numerals
- ✓ Provides suggestions for correction
- ✓ User-friendly interface
- ✓ Educational tool for learning Roman numerals

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/aceoroal/Roman-To-Integer.git
   cd Roman-To-Integer
   ```

2. Ensure you have Python 3.x installed along with Jupyter Notebook:
   ```bash
   pip install jupyter
   ```

3. Navigate to the project directory and launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Usage

1. Open the Jupyter Notebook file in your browser
2. Run the cells to start the Roman numeral validator
3. Enter a Roman numeral when prompted
4. The program will validate your input and provide suggestions if needed

## How It Works

The program follows these steps:

1. **Input Reception**: Accepts user input of a potential Roman numeral
2. **Validation**: Checks the input against Roman numeral rules and patterns
3. **Feedback**: 
   - If valid: Confirms the input is correct
   - If invalid: Suggests the correct Roman numeral format

## Roman Numeral Rules

Valid Roman numerals follow these conventions:

- **I** = 1
- **V** = 5
- **X** = 10
- **L** = 50
- **C** = 100
- **D** = 500
- **M** = 1000

Subtractive notation rules:
- I can be placed before V (5) and X (10) to make 4 and 9
- X can be placed before L (50) and C (100) to make 40 and 90
- C can be placed before D (500) and M (1000) to make 400 and 900

## Requirements

- Python 3.x
- Jupyter Notebook
- Standard Python libraries (no additional external dependencies required)
