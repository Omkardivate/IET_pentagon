# Solid Design Principle

SOLID is a popular set of design principles that are used in object-oriented software development. SOLID is an acronym that stands for five key design principles: single responsibility principle, open-closed principle, Liskov substitution principle, interface segregation principle, and dependency inversion principle. All five are commonly used by software engineers and provide some important benefits for developers.

### Single Responsibility Principle

Following this principle means that each class only does one thing and every class or module only has responsibility for one part of the software’s functionality. More simply, each class should solve only one problem.

Single responsibility principle is a relatively basic principle that most developers are already utilizing to build code. It can be applied to classes, software components, and microservices.

Utilizing this principle makes code easier to test and maintain, it makes software easier to implement, and it helps to avoid unanticipated side-effects of future changes.


### Open-Closed Principle

The idea of open-closed principle is that existing, well-tested classes will need to be modified when something needs to be added. Yet, changing classes can lead to problems or bugs. Instead of changing the class, you simply want to extend it. With that goal in mind, Martin summarizes this principle, “You should be able to extend a class’s behavior without modifying it.”

Following this principle is essential for writing code that is easy to maintain and revise. Your class complies with this principle if it is:

Open for extension, meaning that the class’s behavior can be extended; and
Closed for modification, meaning that the source code is set and cannot be changed.
At first glance, these two criteria seem to be inherently contradictory, but when you become more comfortable with it, you’ll see that it’s not as complicated as it seems. The way to comply with these principles and to make sure that your class is easily extendable without having to modify the code is through the use of abstractions. Using inheritance or interfaces that allow polymorphic substitutions is a common way to comply with this principle. Regardless of the method used, it’s important to follow this principle in order to write code that is maintainable and revisable.