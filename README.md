# Aim: To study and implement Inheritance

# Software Used: VS CODE

# Theory: 

The capability of a class to derive properties and characteristics from another class is called Inheritance. Inheritance is one of the most important features of Object-Oriented Programming.

Inheritance is a feature or a process in which, new classes are created from the existing classes. The new class created is called “derived class” or “child class” and the existing class is known as the “base class” or “parent class”. The derived class now is said to be inherited from the base class.

⮚	MODES OF INHERITANCE
•	Public Mode: If we derive a subclass from a public base class. Then the public member of the base class will become public in the derived class and protected members of the base class will become protected in the derived class.
•	Protected Mode: If we derive a subclass from a Protected base class. Then both public members and protected members of the base class will become protected in the derived class.
•	Private Mode: If we derive a subclass from a Private base class. Then both public members and protected members of the base class will become Private in the derived class.

⮚	TYPES OF INHERITANCE
●	Single inheritance🡪 In single inheritance, a class is allowed to inherit from only one class. i.e. one subclass is inherited by one base class only.

●	Multiple inheritance🡪 In Multiple Inheritance a class can inherit from more than one class. (i.e.) one subclass is inherited from more than one base class.

●	Multilevel inheritance🡪 In this type of inheritance, a derived class is created from another derived class.

●	Hierarchical inheritance🡪 In this type of inheritance, more than one subclass is inherited from a single base class. i.e. more than one derived class is created from a single base class.

# Algorithm:

Algorithm: Demonstrating Inheritance with Animal and Dog Classes

- Start
  
- Define a base class Animal
  
- Create a public method eat() that prints "This animal eats food."
  
- Define a derived class Dog that inherits from Animal
  
- Create a public method bark() that prints "The dog barks."
  
- In the main() function
  
- Declare an object myDog of type Dog
  
- Call myDog.eat() to invoke the inherited method from Animal
  
- Call myDog.bark() to invoke the method defined in Dog
  
- End

Algorithm: Smartphone Class with Multiple Inheritance

1. Start

2. Define Base Class Electronics

Declare a public data member brand and initialize it to "Samsung".

Define a public method model() that prints "Galaxy S21".

3. Define Second Base Class Specs

Declare a public data member battery and initialize it to "4000 mAh".

Define a public method colour() that prints "Phantom Black".

4. Define Derived Class Smartphone

Inherit publicly from both Electronics and Specs.

Declare a public data member sim and initialize it to "Dual SIM".

5. In main() Function

Create an object phone of type Smartphone.

6. Access Members and Methods

Call phone.colour() → inherited from Specs.

Print phone.brand → inherited from Electronics.

Call phone.model() → inherited from Electronics.

Print phone.sim → defined in Smartphone.

Print phone.battery → inherited from Specs.

7. End

Algorithm: Shape, Circle, and Rectangle with Hierarchical Inheritance

1. Start

2. Define Base Class Shape

Declare a public data member color and initialize it to "Red".

Define a public method displayColor() that prints the color.

3. Define Derived Class Circle

Inherit publicly from Shape.

Define a public method area() that prints "Area formula: πr^2".

4. Define Derived Class Rectangle

Inherit publicly from Shape.

Define a public method area() that prints "Area formula: length × width".

5. In main() Function

Create an object c1 of type Circle.

Create an object r1 of type Rectangle.

6. Invoke Methods

Call c1.displayColor() → inherited from Shape.

Call r1.displayColor() → inherited from Shape.

Call c1.area() → defined in Circle.

Call r1.area() → defined in Rectangle.

7. End


# Conclusion:
 Hence we have studied and learnt to implement inheritance





