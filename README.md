# LowLevelDesign - resources
1) https://refactoring.guru/design-patterns
2) https://sourcemaking.com/design_patterns
3) https://www.geeksforgeeks.org/software-design-patterns/
4) https://github.com/prasadgujar/low-level-design-primer
5) https://github.com/DovAmir/awesome-design-patterns#programming-language-design-patterns
6) https://www.youtube.com/watch?v=OkC7HKtiZC0&list=PLGLfVvz_LVvQ5G-LdJ8RLqe-ndo7QITYc (for UML 2.0)
7) https://github.com/iluwatar/java-design-patterns
8) https://github.com/anomaly2104/ticket-booking-low-level-system-design
9) https://github.com/gazbert/java-design-patterns
10) Udit Agarwal System Design (LLD)--> https://github.com/anomaly2104

---------------------------------S.O.L.I.D Principles --------------------------------------------
These are five design principles that improve the maintainability of Object-Oriented software.

**Principle	Description	Example**

**Single Responsibility Principle (SRP)**	A class should have only one reason to change.	Separate AccountService and TransactionService instead of combining them.

**Open/Closed Principle (OCP)**	A class should be open for extension, but closed for modification.	Use abstract classes or interfaces to allow extension without modifying existing code.

**Liskov Substitution Principle (LSP)**	A subclass should be replaceable for its base class without breaking functionality.	If SavingsAccount extends BankAccount, it should support all behaviors of BankAccount.

**Interface Segregation Principle (ISP)**	A class should not be forced to implement unnecessary methods.	Instead of one big interface, break it into smaller ones (LoanService, CreditCardService).

**Dependency Inversion Principle (DIP)**	High-level modules should not depend on low-level modules. Both should depend on abstractions.	Use interfaces instead of direct class dependencies. (DatabaseService interface instead of MySQLDatabase).



--------------HTTP Code ------------

1xx – informational – the request was received, continuing process
2xx – successful – the request was received successfully and accepted
3xx – redirection – further action needs to be taken to complete the request
4xx – client error – request contains bad syntax or cannot be fulfilled
5xx – server error – the server failed to fulfill an apparently valid request
 ----- Status codes meaning --------
200- ok
201- created
301 - found
400 -bad request
401 - unauthorized
403 -forbidden
404 - not found
405 - method not allowed 
408 - request timedout
413 - request entity too large 
429 - too many requests

#For Angular

https://github.com/sudheerj/angular-interview-questions?tab=readme-ov-file
