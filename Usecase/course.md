Relationships in use case diagrams
There are four different types of relationships in a use case diagram:

**Association**: This shows the relationship between and among actor(s) and use case(s). It represents how an actor can perform certain functions. It is denoted by a solid line without arrows. All the actors in a use case diagram must have at least one association with any use case. More than one actor can be associated with the same use case, and a single actor can be associated with more than one use case.

**Generalization**: This relationship is also known as inheritance. In inheritance, we have parent and children classes. Similarly, in a use case diagram, we have parent and child use cases. The child use case has generalization with the parent use case. Each child inherits the behavior of its parent. It is denoted by a solid line with an arrow on only one side (toward the parent use case).

**Include**: We use this to show the relationship between two use cases. It shows that one use case includes the behavior of another use case. The included use case will execute only after the execution of the base use case. We can also say that the base use case requires an included use case in order to be completed. It is represented by a dashed line with an arrow on only one side (toward the included use case), and we write <<include>> above the line.

**Extend**: We use this to show the relationship between two use cases. It shows that one use case extends the behaviors of another use case. The extended use case does not execute every time. It always depends on certain conditions. It is used to extend the functionality of the base use case. It is represented by a dashed line with an arrow on only one side (toward the base use case), and we write <<extend>> above the line.

In the example below, we have a small ATM (automated teller machine) transaction system where customers can transfer funds and make payments. To validate the funds, the transfer system has to check if a sufficient amount of funds is available. Otherwise, an error message will be displayed. To make a payment, a customer has two choices. It can either pay via a current account or a savings account.

![image](https://github.com/user-attachments/assets/1db7afa8-f410-41c1-a409-6196fbdbe864)

**Benefits of use case diagrams**
A use case diagram is important in the following scenarios:

It explains the flow and objective of all use cases.

It helps in understanding the high-level functional requirements of the system.

It defines a system's context and needs.

It explains system behavior from a user perspective.

It explains the scope of the system.
