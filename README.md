# CSC510-HW2

### Name: 
Navjot Singh
### Student Id: 
200154743
### Unity Id: 
nsingh9@ncsu.edu

### OO Patterns
#### Creational Patterns
* **Builder Pattern**: The builder pattern is used to simplify the object creation process where one kind of input is expected to create different kinds of complex representations. A separation between the representation and the construction of representation is provided with the help of a builder object. This is in contrast to using various constructors as builder object receives initialization parameters step by step and returns the resulting constructed object at once.

* **Singleton Pattern**: When a class wants to ensure that there is only one instance of it which can be accessed only from one single point of access, it enforces the creation of Singleton Pattern. It is done by creating a public accessor function implementing lazy initialization approach to create a private static instance of the object. The constructor of the function is hidden by making it private and the public accessor function returns the static instance if the object is already created, otherwise, creates the first object and then returns it.

#### Structural Patterns
* **Adapter Pattern**: When the functionality of an already existing system is intended to be used in a new way which requires some kind of intermediate layer that maps the new input system to the old systems' expected set of inputs. A wrapper class is used to wrap an old interface to provide a new interface which accepts inputs according to the new system but provides the same functionality as that of the old class.

* **Decorator Pattern**: This pattern allows to add functionality to a class at runtime without the use of inheritance. We do this by creating an abstract wrapper interface from which both the decorator and the core object inherit. The core object becomes hidden inside a decorator object with this pattern. 

#### Behavioral Patterns

