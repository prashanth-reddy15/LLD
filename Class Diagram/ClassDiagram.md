Popular notations in the class diagram
The following are some essential notations of the class diagram:

**Class notation**
Interface, abstract class, and enumeration

Access modifiers

**Class notation**
A class is represented by a rectangle with three sections. The first section holds the class name, the second one lists the attributes, and the third one shows the methods (operations). The following is the depiction of a `Movie` class with its attributes and methods.
![image](https://github.com/user-attachments/assets/d9dea894-e1c7-473e-8a98-56e4068fce8b)

Interface, abstract class, and enumeration
We can declare a class as abstract using abstract keywords. The class name will be printed in italic. We can use the interface, annotation, and enum keywords too. The illustration below shows how to depict these notations in a class diagram.
![image](https://github.com/user-attachments/assets/a72763d9-0d1a-41bd-8dd8-9f4584f78752)

**Access modifiers**
You may use character symbols to specify the visibility of the associated object when defining methods or attributes. The most widely used access modifiers are as follows:

**Public**: A public member can be seen anywhere in the system. It is represented by a + symbol.

**Private**: Members can only be accessible from within the class. It is inaccessible from outside the class. It is represented by a - symbol.

**Protected**: Members are only accessible within the class and derived classes. It is represented by the # symbol.

The following images show how to use the access modifiers in the class diagram:
![image](https://github.com/user-attachments/assets/8bcfed2f-da49-42aa-9df5-85332ba9f860)

**Association**
Association provides a mechanism to communicate one object with another object, or one object provides services to another object. Association represents the relationship between classes.

The association can be divided into two categories:

**Class association (Inheritance)**
**Object association**
![image](https://github.com/user-attachments/assets/597c05fb-1055-4706-b826-5d81262f52b7)

**Class association**
Inheritance falls under the category of class association. Creating a new class from the existing class(es) is called inheritance. Apart from its own behaviors and attributes, the child class inherits the characteristics of its parent(s). A solid line leads from the child class to the parent class with a hollow arrowhead representing the inheritance relationship.

The following class diagram represents the inheritance relationship:
![image](https://github.com/user-attachments/assets/13ca3633-06eb-43a6-9650-af563d489e19)

**Object association**
Object association (relationship between objects) can be divided into the following categories:

  1. **Simple association**

  2. **Composition**

  3. **Aggregation**

**Simple association**
The weakest connections between objects are made through simple association. It is achieved through reference, which one object can inherit from another. The following is an example of a simple association:
![image](https://github.com/user-attachments/assets/1127adf4-a01b-41e4-b226-150176e31774)

**Aggregation**
Aggregation describes the relationship between the container and the object it contains. An object may contain an aggregate of another object. Aggregation is denoted by a line with an unfilled diamond head towards the container.

Aggregation is a weaker relationship because:

Aggregate objects are not a part of the container.

Aggregate objects can exist independently.
![image](https://github.com/user-attachments/assets/708c60e7-d9cf-4523-a46d-9cf4d1c14445)

**Composition**
An object may be composed of smaller objects, and the relationship between the “part” objects and “whole” objects is known as composition.

In the example below, the Chair class can be composed of other objects of Arm, Seat, and Leg types. Composition is denoted by a line with a filled diamond head at the composer class pointing to the component class.

Composition is a strong relationship because:

The composed object becomes a part of the composer.

Composed objects can not exist independently.
![image](https://github.com/user-attachments/assets/5e42971a-ebb4-4bbd-834e-3cfecdc45901)

**Some additional types of association**
The following are some types of simple associations based on navigation:

Single-direction navigation is called one-way association and is denoted by an arrow toward the server object.
![image](https://github.com/user-attachments/assets/ef882667-263c-4e6b-bf3c-04933d1b67b1)

If we navigate in both directions, the association is called a two-way association and is denoted by a line between two objects.
![image](https://github.com/user-attachments/assets/b10dee12-beca-42de-8fda-249810309df8)

Binary, ternary, and n-ary associations are based on the number of objects.

Association in which two objects are involved is called a binary association. The binary association includes one-way or two-way navigation.

Association between the objects of exactly three classes is a ternary association and is denoted by a diamond with lines connected to associated objects.

Association between more than three classes is called n-ary association.
![image](https://github.com/user-attachments/assets/7a61515e-5ace-4759-bbc1-84abb02e5944)

**Dependency**
Dependency indicates that one class is dependent on another class(es) for its implementation. Another class may or may not depend on the first class. A dashed arrow denotes dependency.
![image](https://github.com/user-attachments/assets/55f37524-f081-4b96-a317-405fdbd623ef)

In the example above, we have two classes—RegistrationManager and Student. The RegistrationManager class relies on the Student class for its behavior because the object of the Student class is passed as a parameter to one of the functions in the RegistrationManager class.
