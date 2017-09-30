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

Example: As a program that handles the request to prepare meals at a fast food chain which follow the same construction process (one burger, one cookie, one drink etc.), builder pattern is the ideal choice. This pattern then constructs the meal plan object along with allowing the type of the individual item (cheeseburger, hamburger) in the meal plan to be different.

* **Singleton Pattern**: When a class wants to ensure that there is only one instance of it which can be accessed only from one single point of access, it enforces the creation of Singleton Pattern. It is done by creating a public accessor function implementing lazy initialization approach to create a private static instance of the object. The constructor of the function is hidden by making it private and the public accessor function returns the static instance if the object is already created, otherwise, creates the first object and then returns it.
   Example: This is most commonly used in the case of creating a logger class which is used to log the different operations being done in the system. Without having to create the logger object every single time there's a need to log, a single global instance of logger is accessed to perform the function.

#### Structural Patterns
* **Adapter Pattern**: When the functionality of an already existing system is intended to be used in a new way which requires some kind of intermediate layer that maps the new input system to the old systems' expected set of inputs. A wrapper class is used to wrap an old interface to provide a new interface which accepts inputs according to the new system but provides the same functionality as that of the old class.

* **Decorator Pattern**: This pattern allows to add functionality to a class at runtime without the use of inheritance. We do this by creating an abstract wrapper interface from which both the decorator and the core object inherit. The core object becomes hidden inside a decorator object with this pattern. 

#### Behavioral Patterns
* **Iterator Pattern**: This pattern is used to sequentially iterate over the elements of an object without exposing the underlying representation. To iterate over the List data structure for example, we delegate the work to an Iterator object that provides a common way to iterate sequentially without List having to expose its inner structure to provide the same functionality.

* **Memento Pattern**: This pattern is useful when we want to provide the functionality to undo or rollback the current state to some previous state without providing access to private variables and hence, violating encapsulation. This is done with the help of three objects: caretaker, originator, ,memento. Originator is the object whose internal state needs to be restored. Before making any new changes to the originator, caretaker asks for a memento object and then makes the changes to the originator. To undo the changes now, memento object is returned to the originator. 

### Free Style Patterns:
 * **Model View Controller Pattern**: MVC is an architectural pattern that divides the implementation of user interface into three interconnected parts. The three representations are the ways the information is received from the user, the way information is sent back to the user, and the way information is internally represented. This decoupling helps in code reuse and parallel development. This is now commonly used in languages and frameworks aimed at developing web applications like Ruby on Rails, Java Struts, etc.
 * **Reference Count (Linux Kernel design patterns)**: The idea of a reference counter is to manage the lifetime of an object by incrementing whenever a new reference is taken and decrementing when a reference is released. When this counter reaches zero any resources used by the object (such as the memory used to store it) can be freed. The mechanisms for managing reference counts seem quite straightforward. However there are some subtleties that make it quite easy to get the mechanisms wrong. Partly for this reason, the Linux kernel has (since 2004) a data type known as "kref" with associated support routines. As noted above, names for design patterns are very valuable and just providing that name for kernel developers to use is a significant benefit for reviewers. This inclusion of kref in the Linux kernel gives both a tick and a cross to the kernel in terms of explicit support for design patterns. A tick is deserved as the kref clearly embodies an important design pattern, is well documented, and is clearly visible in the code when used. ( [source](https://lwn.net/Articles/336224/))
 * **Abstract Data Types**: The idea behind Abstract Data Types is to encapsulate the entire implementation of a data structure, and provide just a well defined interface for manipulating it. The benefit of this approach is that it provides a clean separation. The data type can be implemented with no knowledge of the application which might end up using it, and the application can be implemented with no knowledge of the implementation details of the data type. Both sides simply write code based on the interface which works like a contract to explicitly state what is required and what can be expected. ( (Source)[https://lwn.net/Articles/336255/] )


### SELENIUM
[LINK TO WebTest.java](https://github.ncsu.edu/nsingh9/CSC510-HW2/blob/master/Selenium/src/test/java/selenium/tests/WebTest.java)
