# Calculator Assignment

This repository hosts a Java application intended as an educational tool to demonstrate the practical use of interfaces and class inheritance in Java programming. The application's focus lies in computing the area and perimeter of geometric shapes like Circles, Triangles, and Rectangles. It exemplifies the implementation of interfaces and inheritance to craft a modular and adaptable design.
The core objective of this assignment is to offer hands-on experience with Object-Oriented Programming (OOP) principles, with a particular emphasis on interfaces and inheritance. Users engage with the application by inputting dimensions for various shapes, after which the program calculates and presents the area and perimeter based on the provided inputs.

### Features

- **Interface Implementation:** The `Shape` interface defines the necessary methods for area and perimeter calculations, which are then implemented by concrete shape classes.
- **Class Inheritance:** Concrete classes like `Circle`, `Triangle`, and `Rectangle` extend the `Shape` interface, illustrating polymorphism and code reuse.
- **User Input Handling:** The application effectively manages user input for shape dimensions, facilitating dynamic calculations.
- **Area and Perimeter Calculation:** For each selected shape, the application computes and displays both the area and perimeter.

### Code Structure

- **Shape Interface:** Establishes the common blueprint for all shape classes.
- **Circle Class:** Implements the `Shape` interface to represent a circle, providing methods for area and perimeter calculations.
- **Triangle Class:** Represents a triangle and implements the `Shape` interface for area and perimeter computation.
- **Rectangle Class:** Represents a rectangle and implements the `Shape` interface for area and perimeter calculation functionalities.
- **Main Class:** Orchestrates the application's execution through the `main` method, demonstrating shape class usage and handling user interactions for input.
