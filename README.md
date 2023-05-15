# OOP Week 9 Forum: Class Design and Implementation Case

A large company with locations in different cities has taken an OOP approach in creating an administration program that manages all aspects of its business. These aspects include:

·the sale of all the different products that the company manages

·the salaries for managers, office staff and sales personnel.

### 1.(a) By making use of an example from the above scenario, distinguish between a class and an instantiation of a class. (3 points) 
A class is the blueprint which defines the object's properties, behaviors, and methods. While the instantiation of a class is the specific objects that uses this class/blueprint.<br><br>
Example of this from the above scenario: Some classes that can be created are 'Product' and 'Staff', examples of the instantiation of these classes respectively are 'MacBook Pro' and 'Steve Rogers'.

### The different modules in the program each open a graphical user interface (GUI). Each GUI has a similar design but contains differences specific to each module.(b) By giving two examples, explain how the principles of inheritance can be incorporated into the design of this administration program. (4 points)

Using the principles of inheritance, we can first create a GUI class which contains all the basic properties of a GUI that the different modules may have in common. We can then create classes for each modules that inherits the first/basic GUI class containing the basic feautures of the GUI, and then add special/specific features that the specific modules have. <br>

Example: We first create a base class for the GUI, the sales module will then inherit this base class and have a 'calculate average sales/month' method added , while the salary module will inherit the base class and have a 'view highest salary' method added. 

