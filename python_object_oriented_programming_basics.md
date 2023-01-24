# Object Oriented Programming (OOP)

- Python is design is based around objects rather than functions and logic.
- Each object is created using a blueprint known as a class.
- Each class has attributes to contain the data an object needs to work with.
- Each class also contains functions, called methods that perform operations on objects.
- An object is an instance of a class. Example: you can have a class called "cars" and use it to define an object called "Honda"

## 4 Principles of OOP
- <b>Encapsulation</b>
    - Restricts access to methods and attributes within a certain class. 
    - This prevents accidental modification of data and unwanted changes to other objects.

- <b>Inheritance</b>
    - A class can inherit all the methods and attributes from another class. 
    - If a class called “person” had the attributes name, age, and dob, we could use this class to define two other child classes called “student” and “staff.” Both inherit the methods and attributes from the “person” class.

- <b>Polymorphism</b>
    - Polymorphism allows us to define methods in the child class with the same name as defined in the parent class. 
    - This is known as method overriding. 
    - Polymorphism also allows us to define methods that can take many forms.

- <b>Abstraction</b>
    - Abstraction is the process of reducing objects to their essence so that only the necessary elements are represented. 
    - In other words, you remove all irrelevant information about an object in order to reduce its complexity.

# Classes & Objects
- Define a class using keyword: class

![Class](https://user-images.githubusercontent.com/111991325/214202702-b1c95b5c-130f-4dbb-b713-d2f05016833d.jpg)

- All classes have a function called <b> init() </b>, which is automatically executed when the class is initiated. 
- init() function is used to initialize attributes

![Self](https://user-images.githubusercontent.com/111991325/214204156-7ee0c973-b3fd-4e72-8e3e-9d9332c27de7.jpg)

- By using the keyword <b>self</b>represents the current instance of the class (i.e., the object created from the class). By using the self keyword, you can access the attributes of the object itself.
- When you declare a method, you pass the current instance of the class (i.e., the object itself), along with any other parameters required, to the method:

![Method](https://user-images.githubusercontent.com/111991325/214204379-a5c5039a-a0d7-4d54-9804-4a1431e88837.jpg)
