# LLD
Low Level Design interview notes:

UML Types:
**1. Use case Diagrams:
**
A UML use case diagram summarizes the interactions between a system and its users. A use case diagram can be made for a general scenario or multiple scenarios that encapsulate the system’s functioning.

The use case diagram displays three kinds of entities: the system, the actors, and the use cases. The system is represented by a box encompassing the use cases. The actors are users or systems that interact with the main system and are represented by figures. The use cases are functions performed by the actors interacting with the system. Ellipses represent use cases.

To represent complex relationships between different use cases, we can use the extend and include relationships.

Extend relationship: The use case is optional and comes after the base use case. It is represented by a dashed arrow in the direction of the base use case with the notation <<extend>>.

Include relationship: The use case is mandatory and part of the base use case. It is represented by a dashed arrow in the direction of the included use case with the notation <<include>>.


**Use case diagram
**![image](https://github.com/user-attachments/assets/6ce67e02-e64d-4776-8454-22ef6cf4129c)


Use case diagram
In the above use case diagram, the use case “Read book” includes the use case “Open book”. If a reader reads the book, she must open it too, as it is mandatory for the base use case (read book). The use case “read book” extends to the use case “turn page”, which means that turning the page while reading the book is optional. The base use case in this scenario (read book) is complete without the extended use case.
