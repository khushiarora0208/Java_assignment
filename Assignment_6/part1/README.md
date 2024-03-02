**Java Stack Project**

This project demonstrates the implementation of stack structures in Java, showcasing versions for both fixed-size and dynamically resizable stacks. It also includes examples illustrating the usage of interfaces.

**Interfaces**

- **Interface_STK**: Defines stack operations such as addition, removal, display, and checks for fullness and emptiness. Both the `Fixed_stk` and `Growable_stk` classes implement this interface to ensure they support these stack actions.

- **Interface1**: A basic interface containing two methods, `method1` and `method2`, serving as a demonstration of interface usage in Java.

**Classes**

- **Student**: Represents a student with attributes like a unique PRN, name, and grades, providing a simple model for understanding the concept.

- **Fixed_stk**: Implements `Interface_STK` to create a fixed-size stack using an array. It allows adding, removing, and displaying items while ensuring the stack doesn't exceed its set size.

- **Growable_stk**: Also utilizes `Interface_STK` to construct a stack capable of dynamically resizing using an ArrayList. It demonstrates how a stack can adjust its size to accommodate more items, similar to `Fixed_stk` but with flexibility in size management.

- **Interface_implementation**: Demonstrates the usage of methods from `Interface1`, providing simple implementations for `method1` and `method2`, such as displaying messages.

- **InterfaceDemo**: Utilizes `Interface_implementation` to showcase interface methods in action, creating an instance and using its methods for demonstration.

- **StackDemo**: The main class exhibiting stack functionality. It includes examples for both `Fixed_stk` and `Growable_stk`, demonstrating addition, removal, and display operations, showcasing the usage of stacks with fixed and dynamic sizes in Java programs.
