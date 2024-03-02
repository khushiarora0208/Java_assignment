The Student Records Management Application in Java provides a user-friendly menu-based system for handling student records efficiently. It supports essential tasks such as adding new students, displaying student details, searching for students by various attributes, updating student data, and removing students from the records.

**Student Class**
The Student class serves as a blueprint for individual students, encapsulating attributes like their Permanent Registration Number (PRN), name, date of birth (DOB), and academic marks.

**Attributes:**
- PRN: Unique identifier for each student.
- Name: Full name of the student.
- DOB: Date of birth of the student (formatted as dd/MM/yyyy).
- Marks: Academic performance of the student.

**Constructors:**
- Student(int prn): Initializes a student object with a PRN.
- Student(int prn, String name): Initializes a student object with a PRN and name.
- Student(int prn, String name, String dob): Initializes a student object with a PRN, name, and DOB.
- Student(int prn, String name, String dob, double marks): Initializes a student object with a PRN, name, DOB, and marks.

**Methods:**
- getPrn(): Retrieves the student's PRN.
- setPrn(int prn): Sets the PRN for the student.
- getName(): Retrieves the student's name.
- setName(String name): Sets the name for the student.
- getDob(): Retrieves the student's DOB.
- setDob(String dob): Sets the DOB for the student.
- getMarks(): Retrieves the student's marks.
- setMarks(double marks): Sets the marks for the student.
- toString(): Provides a textual representation of the student.

**StudentFunctions Class**
The StudentFunctions class contains methods to perform various operations on the student records.

**Methods:**
- addStudent(): Registers a new student in the database.
- printStudentDetails(): Displays information of all students in the database.
- searchStu(): Searches for a student using their PRN, name, DOB, or marks.
- updateOrDelete(): Offers options to modify or remove student details.
- editStudent(): Allows modifications to a student's information.
- deleteStudent(): Removes a student from the database.

**StudentDemo Class**
The StudentDemo class serves as the entry point of the application, providing a menu-driven interface for interacting with the StudentFunctions class.

**Methods:**
- main(String[] args): The primary method that initiates the application and presents a menu for executing different actions on student records.
