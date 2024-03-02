## Assignment overview
This Java-based system facilitates the management and computation of salaries for employees. It accommodates both normal employees and bonus employees, enabling dynamic salary calculation based on various factors such as basic wage, bonus percentages, and deductions like EPF (Employee Provident Fund) and ESI (Employee State Insurance). The system interacts with the user to input employee details, determines their eligibility for a bonus, and computes the net salary accordingly.

## Classes and Their Roles

- **TestEmployee**: The primary class responsible for user interaction. It prompts the user to specify the employee type (bonus or normal) and proceeds with the salary calculation based on the chosen category.

- **Employee (Abstract Class)**: Acts as the base class for both NormalEmployee and BonusEmployee classes. It defines common properties and methods required for salary computation, including the abstract method `salaryCalculation()` implemented by subclasses.

- **NormalEmployee**: Extends the Employee class and represents employees without a bonus. It provides constructors for testing and instantiation with specific attributes. The `salaryCalculation()` method computes the salary for normal employees.

- **BonusEmployee**: Similar to NormalEmployee but for employees eligible for bonuses. It provides constructors and implements the `salaryCalculation()` method, considering the bonus percentage to calculate the final salary.

## order to run the files
1. Compile the Java files.
2. Run the `TestEmployee` class to initiate the program.
3. Follow the prompts in the console to input employee details, including bonus eligibility, monthly bonus amount (if applicable), employee ID, department, date of joining, UAN, PF number, bank name, bank account number, gross wage, and leaves taken.
4. Based on the input, the program calculates and displays the employee's salary details, encompassing basic wage, HRA (House Rent Allowance), conveyance allowance, medical allowance, other allowances, total earnings, EPF, ESI, total deductions, and net salary.
