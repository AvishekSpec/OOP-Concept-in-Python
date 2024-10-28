OOP (Object Oriented Programming)
•	Object Oriented Programming is a way of programming that uses “objects” to represent data and methods.
 
![image](https://github.com/user-attachments/assets/ffeb286d-a43f-4665-ba1a-c8498eb62ad9)

OOP Concepts
•	Class
•	Objects
•	Methods
•	Inheritance
•	Polymorphism
•	Data abstraction
•	Data encapsulation

Class: 
•	collection of objects defining the common attributes and behaviors
•	is defined under a keyword “ class”
Example: 
class Class1(): // class 1 is the name of the class


Object:
•	an instance of a class
•	has state and behavior and can access the data
Syntax: 
obj = class1()
Here, obj is the object of class1.

Class and Object Creation in Python 
![image](https://github.com/user-attachments/assets/1e5b4738-2e08-4a02-a66a-ef318c71038b)
•	employee1() and employee2() are the objects instantiated against the class ”employee”.
•	the word (__dict__) is a “dictionary” which prints all the values of object ‘emp1’ against the given parameter (name, age, salary).
•	(__init__) acts like a constructor that is invoked whenever an object is created.

OOP Methodologies

Inheritance
•	Inheriting or transfer of characteristics from parent to child class without any modification. 
•	The new class is called the derived/child class and the one from which it is derived is called a parent/base class
     
Types of Inheritance:
![image](https://github.com/user-attachments/assets/437ffdd3-c573-4d76-9d02-c85e0af57891)

Single Inheritance:
•	Enables a derived class to inherit characteristics from a single parent class
![image](https://github.com/user-attachments/assets/3704cedb-d074-462b-8fd1-9061a88da9f7)
•	I am taking the parent class and created a constructor (__init__),  class itself is initializing the attributes with parameters(‘name’, ‘age’ and ‘salary’).
•	Created a child class ‘childemployee’ which is inheriting the properties from a parent class and finally instantiated objects ’emp1′ and ’emp2′ against the parameters.
•	Finally, I have printed the age of emp1. Well, you can do a hell lot of things like print the whole dictionary or name or salary.

Multilevel Inheritance
•	Enables a derived class to inherit properties from an immediate parent class which in turn inherits properties from his parent class.
![image](https://github.com/user-attachments/assets/42e90488-d17b-49c3-a100-4f82106a8054)
•	In the above program, employee is the super class, childemployee1 is the child class. The childemployee1 class acts as the parent class for class childemployee2.
•	Two objects emp1 and emp2 are instantiated from superclass and parent class respectively by passing the parameters like name, age and salary.

Hierarchical Inheritance
Hierarchical level inheritance enables more than one derived class to inherit properties from a parent class.
![image](https://github.com/user-attachments/assets/f136c258-b336-4301-b054-119607005c42)
 
Multiple Inheritance
Multiple level inheritance enables one derived class to inherit properties from more than one base class.
![image](https://github.com/user-attachments/assets/aafb6ffc-b405-46b0-b111-369a47a33ab3)

