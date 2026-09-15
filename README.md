# Calculator

A simple **Calculator Application** developed using Java. This is a console-based project that performs basic arithmetic operations.

## Features

* Addition
* Subtraction
* Multiplication
* Division
* Division-by-zero validation
* Interactive console menu
* Continuous calculations until the user exits

## Technologies Used

* Java
* Scanner
* Methods
* Switch statements
* Conditional statements
* Loops

## Project Structure

```text
calculator-java/
│
├── src/
│   └── Calculator.java
│
├── README.md
└── .gitignore
```

## Operations

The calculator supports the following operations:

| Operation      | Description                                |
| -------------- | ------------------------------------------ |
| Addition       | Adds two numbers                           |
| Subtraction    | Subtracts the second number from the first |
| Multiplication | Multiplies two numbers                     |
| Division       | Divides the first number by the second     |

## How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/calculator-java.git
```

### 2. Open the Project

Open the project using a Java IDE such as:

* IntelliJ IDEA
* Eclipse
* NetBeans
* VS Code

### 3. Compile the Program

Navigate to the `src` directory:

```bash
javac Calculator.java
```

### 4. Run the Program

```bash
java Calculator
```

## Main Menu

```text
==============================
          CALCULATOR
==============================
1. Addition
2. Subtraction
3. Multiplication
4. Division
5. Exit
==============================
Enter your choice:
```

## Example

### Addition

```text
Enter your choice: 1
Enter first number: 25
Enter second number: 15
Result: 40.0
```

### Multiplication

```text
Enter your choice: 3
Enter first number: 10
Enter second number: 5
Result: 50.0
```

### Division

```text
Enter your choice: 4
Enter first number: 20
Enter second number: 4
Result: 5.0
```

### Division by Zero

```text
Enter your choice: 4
Enter first number: 20
Enter second number: 0
Error: Cannot divide by zero.
```

## Concepts Used

This project demonstrates:

* Java classes and methods
* Scanner for user input
* switch statements
* if-else conditions
* while loops
* Arithmetic operators
* Input validation
* Basic error handling

## Future Improvements

The calculator can be upgraded by adding:

* Modulus operation
* Power calculation
* Square root
* Percentage calculation
* Scientific calculator functions
* Calculation history
* Java Swing GUI
* JavaFX interface
* Expression evaluation

## Learning Objective

The purpose of this project is to practice Java fundamentals including methods, loops, switch statements, conditional statements, user input, and arithmetic operations.

## License

This project is created for educational purposes.
