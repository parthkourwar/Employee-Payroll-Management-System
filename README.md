# Employee-Payroll-Management-System

The Employee Payroll Management System is built by using core Java focused on studying and understanding the implementation of Object Oriented Programming.
This System consists of implementation of various OOP concepts like encapsulation, inheritance, data hiding, abstraction, etc.

The Structure of the System is as follows:
  The whole system is divided into 4 Classes:
    1) Employee
    2) FullTimeEmployee
    3) PartTimeEmployee
    4) PayrollSystem

  1) Employee:
     This is the class where the basic variables that the class should contain to describe the boject are defined.
     eg. Name, id.
     It has getrr methods to help us encapsulate the data. The vairables are not directly accessible outside the class.
     Employee is the parent class for all the classes.
     It has a abstract class named calculateSalary() which is defined by the child classes.
  2) FullTimeEmployee:
     FullTimeEmployee class extends the Employee class.
     It has variables like monthlySalary.
     As the monthly salary is declared by the constructor, the calculateSalary() method only returns the monthlySalary.
  3) PartTimeEmployee:
     This class also extends the Employee class.
     It has variables like hoursworked and hourlyrate.
     The abstract class here returns the calculate value from the given information    
  4) PayrollSystem
     Here a arraylist is created to store all the employees.
     This class has methods to add and delete employees from the arraylist.

The Main Class have the object initation and use of various methods in all the classes.

Conclusion:
This project focuses on complete understanding the implementation of core Java and Object oriented Programming concepts.
This System can handle the records of employees and their salary details.
