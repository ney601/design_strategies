# Design Strategies

### 1. What do we mean by coupling and cohesion when discussing structured design?

Coupling describes the level of interdependence present between software modules. Low coupling refers to when modules are independent and therefore chsnges in one modules will have little impact on other modules. Whereas high coupling refers to when modules are strongly interdependent or closely connected and therefore will greatly impact other modules when changes are made in one module.

Choesion describes the level to which elements within a module are related to each other and work to serve a single purpose. Low cohesion means that the elements are loosely related and therefore serve multiple purposes. High cohesion means that the elements are closely related and therefore serve a single purpose.

### 2. What is the difference between top-down and bottom-up design? Which best describes a function oriented design?

Top-down design gives an overview of the system, which is broken into smaller modules, and then further broken into finer details. Bottom-up design specifies each, individual part of the design in detail, which is then linked to form a complete system.

Function-oriented design is best described by a top-down design, as the system is refined by a hierarchy of increasing levels of details.

### 3. In which design methodology would a class diagram be most useful?

Class diagram would be most useful in an object-oriented design methodology, for example UML designing, as they clearly map out the structure of the system using its properties and methods.

### 4. What are the four pillars of object oriented programming? Give a single-sentence description of each.

Abstraction - Process of exposing only the functionality and the necessary aspects of the program.
Encapsulation - Process of budling together code(methods) and data into a single unit.
Inheritance - Process of creating a class that inherits properties and methods from another class.
Polymorphism - The ability of objects from different classes to be treated as objects of a common superclass. 

### 5. What is the strategy pattern? How would its implementation differ between a functional and object oriented system?

### 6. Imagine your is creating a new online payment system. In order to gain maximum market share it can't be tied to a particular sector - it needs to work just as well when ordering a takeaway as when buying a new coat. Which design methodology would you suggest following? Give some justification for your decision.
