## Design Patterns

##### Creational pattern

1. Factory Pattern
   - Factory pattern uses when we need any object based on some codition.
   - we pass the string value for which class we have to create object and that factory will return the object as per aurgument.
2. Abstract Factory Pattern
   - Abstract Factory pattern uses when we need any specific category of factory is required.
   - we create one main factory first and than create multiple child factories as per different categories.
3. Builder Desing Pattern
   - If we have multiple optional properties in class than we have huge costructor to fill all the properties of that class. or we want to create constructor for some of the properties only.
   - if we want to create multiple combinations of properties to initialize property. our code goes lengthy and we may be not use all of them in some cases. in such a cases we can use Builder DP.
   - Builder DP is also called as **Step by Step object creation**.
   - we initialize each property using saperate method for that perticular property. After initializing all properties we can build object using **Build()** Method.
   - StringBuilder is best example of Builder DP
4. Prototype Design Pattern
   - These pattern is used when we need to create clone/copy of existing object.
   - we can do some minor modification on the new objects.
   - we can create one interface (Prototype) with method clone() which should be implemented by all the child classes.
5. Singleton Pattern
   - we use singleton pattern when we need only 1 instance of class and we can utilize that object only.
   - example is DB connection. we may want only 1 DB connection.
   - Different method to achieve these:
     1. Eager
     2. Lazy
     3. Synchronized Method
     4. Double Locking

- Examples: [Repo](https://github.com/shabbirdwd53/design_patterns)
