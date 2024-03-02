This Java application serves as a user-friendly student management system, allowing users to input student data, view profiles, compute scores, and terminate the program through a menu-driven interface.

**Classes and Interfaces**

**Main Class**
The Main class acts as the entry point of the application. It displays a menu to users and handles input processing to execute various functions.

- **Methods:**
  - main(String[] args): Initializes the program and presents a menu for user interaction.

**Result Class**
Extends the Student class and implements the Exam interface. This class calculates and displays a student's results based on their scores.

- **Attributes:**
  - percentage: Represents the computed percentage for a student.

- **Methods:**
  - Result(): Constructor to initialize initial values.
  - Percent_cal(): Computes the student's percentage from their scores.
  - enterStudentDetails(Scanner scanner): Accepts input for a student's details through user interaction.
  - displayStudentInfo(): Displays the student's information.
  - displayResult(): Shows the computed score for the student.
  - toString(): Provides a textual description of the Result object.

**Exam Interface**
Defines the Percent_cal() method, which calculates a student's percentage. Classes implementing this interface must implement this method.

- **Methods:**
  - Percent_cal(): Abstract method to be implemented for computing a student's percentage.

**Student Class**
Represents individual students with attributes such as name, roll number, and scores.

- **Attributes:**
  - name: Name of the student.
  - roll_no: Roll number of the student.
  - mark1, mark2: Scores attained by the student.

- **Methods:**
  - Student(String name, int roll_no, double mark1, double mark2): Constructor to initialize a student with specific details.
  - Accessor and mutator methods for attributes.
  - toString(): Provides a textual representation of the student.
