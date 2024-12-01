# 🧮 WPF Calculator

A simple yet powerful calculator built with WPF that supports basic arithmetic operations and chained calculations. This project was developed as part of the M7 - Interface Development course.

## 📋 Table of Contents

- [System Requirements](#-system-requirements)
- [Features](#-features)
- [Installation Guide](#-installation-guide)
- [Usage Guide](#-usage-guide)
- [Examples](#-examples)
- [Technical Implementation](#-technical-implementation)
- [License and Author](#-license-and-author)
- [Conclusions](#-conclusions)

## 💻 System Requirements

- Windows Operating System
- .NET 8.0 or higher
- Visual Studio 2022 (for development)
- At least 50MB of free disk space
- Minimum 4GB RAM recommended

## ✨ Features

- Basic arithmetic operations (addition, subtraction, multiplication, division)
- Support for chained operations
- Operator precedence handling (* and / before + and -)
- Error handling for invalid operations
- Keyboard NumPad support
- Clear function to reset calculations
- Real-time display of operations

## 📥 Installation Guide

- Clone the repository:
- Copygit clone [repository-url]

- Open the solution file (PAC4-Calculadora.sln) in Visual Studio 2022
- Build the solution (Ctrl + Shift + B)
- Run the application (F5)

## 📖 Usage Guide

# Starting the Calculator

- Launch the application from Visual Studio or the compiled executable
- The calculator window will appear with a clean display


# Performing Calculations

- Enter numbers using the on-screen buttons or your keyboard's NumPad
- Use operation buttons (+, -, *, /) to perform calculations
- Press '=' or Enter to see the result
- Press 'C' to clear the display and start over


# Chained Operations

- You can perform multiple operations in sequence
- Operations follow standard mathematical precedence
- Example: 5 + 3 * 2 will correctly calculate 3 * 2 first



## 💡 Examples

- Basic Calculation
- CopyInput: 5 + 3 =
- Output: 8

- Chained Operations
- CopyInput: 5 + 3 * 2 =
- Output: 11

- Error Handling
- CopyInput: 5 / 0 =
- Output: Error


## 🔧 Technical Implementation
- The calculator is implemented using several key components:

# User Interface

- Built using WPF (Windows Presentation Foundation)
- Responsive grid layout for buttons
- Real-time display updates


# Core Features

- Operation handling through ButcherOperation() method
- Operator precedence managed in Calculate() method
- Error handling for division by zero and invalid operations


# Key Classes

- MainWindow: Main UI and logic implementation
- Event handlers for button clicks and keyboard input
- Helper methods for operation parsing and calculation


# Input Handling

- Support for both mouse clicks and NumPad input
- Input validation to prevent invalid operations
- Real-time display updates



## 📝 License and Author

- Author: Pau Font Montanero
- Course: M7 - Interface Development
- Version: 1.0
- Date: November 2024
- License: MIT License

## 🎯 Conclusions
- This calculator project demonstrates the implementation of a functional WPF application with:

- Clean and maintainable code structure
- Proper error handling
- User-friendly interface
- Support for complex mathematical operations
- Comprehensive documentation

- The project successfully meets all requirements while providing a solid foundation for future enhancements and modifications.
