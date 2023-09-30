## Basic Calculator Using Python (GUI Based)

This project demonstrates the creation of a basic calculator application with a graphical user interface (GUI) using Python and PyQt5. The calculator allows users to perform simple arithmetic operations such as addition, subtraction, multiplication, and division.

## Tech Stack

- **Python**: The core programming language used for building the application.
- **PyQt5**: A Python library for creating desktop applications with graphical user interfaces. PyQt5 is used to design and implement the calculator's GUI components.
  
## Project Structure

The project is organized into several modules, each serving a specific purpose:

1. **test.py**: Initializes the PyQt5 application, creates a window, and displays a simple "hello" message to verify the window functionality.

2. **view.py**: Defines the GUI layout and appearance of the calculator using PyQt5 widgets, including QMainWindow, QLineEdit, QGridLayout, QPushButton, QVBoxLayout, and QWidget. It creates a display bar to show entered digits and positions buttons in the calculator layout.

3. **main.py**: Contains the main function that sets up the application, creates an instance of QApplication, and displays the GUI by calling the GUI() and show() methods.

4. **model.py**: Implements the logic for evaluating mathematical expressions entered by the user. It defines the `evaluateExpression` method to perform the calculation and handle exceptions.

5. **controller.py**: Manages the interactions between the model and view. The Controller class connects user input from the GUI (buttons) to the expression-building logic. It includes functions for calculating results, building expressions, and connecting signals.

## Usage

To run the calculator application:

1. Ensure you have Python installed on your system.

2. Install the required libraries using pip:  (pip install pyqt5),(-sudo apt-get install python3- controller), model, view etc:

## Features

Basic arithmetic operations (+, -, *, /) ,Decimal support, Error handling for invalid expressions.

## Future Work

Add more advanced features, such as trigonometric functions and support for parentheses, Improve the user interface, Add documentation and tests.

## Author
devanshu3
