# The List
List of best practices, principles, patterns, architectures,\
and other things that i've come across while developing software.

Somewhat useful for people trying to learn about software development.\
Mostly consists of things related to OOP, and C#.

Many of the things in this list requires at least an intermediate understanding,\
of general software development principles.

### Basic Elements
 - [Operators](https://www.tutorialspoint.com/computer_programming/computer_programming_operators.htm)
 - [Variables](https://www.tutorialspoint.com/computer_programming/computer_programming_variables.htm)
 - [Datatypes](https://www.tutorialspoint.com/computer_programming/computer_programming_data_types.htm)
    - [Value type](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/value-types)
    - [Reference type](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/reference-types)

### General Elements
 - [Methods](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/methods)
 - [Classes](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/types/classes)
 - [Objects](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/object-oriented/objects)
 - [Expressions](https://exceptionnotfound.net/csharp-in-simple-terms-18-expressions-lambdas-and-delegates/)
 - [Statements](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/statements-expressions-operators/statements)
 - [Conditions](https://www.w3schools.com/CS/cs_conditions.php)

### Fundamentals
 - [Sequence](https://www.bbc.co.uk/bitesize/guides/znh6pbk/revision/2)
 - [Selection](https://www.bbc.co.uk/bitesize/guides/zh66pbk/revision/3)
 - [Iteration](https://www.bbc.co.uk/bitesize/guides/z3khpv4/revision/1)
 - [Recursion](https://www.bbc.co.uk/bitesize/guides/z9hykqt/revision/1)

### Declarations
 - [Modifiers](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/access-modifiers)
 - [Keywords](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/)
 - [Constraints](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/generics/constraints-on-type-parameters)
 - [References](https://stackoverflow.com/questions/40686776/what-exactly-is-a-reference-in-c-sharp)
 - [Pointers](https://www.c-sharpcorner.com/article/pointers-in-C-Sharp/)

### Relationships
 - [Abstraction](https://www.uml-diagrams.org/abstraction.html)
 - [Inheritance](https://stackify.com/oop-concept-inheritance/)
 - [Composition](https://www.uml-diagrams.org/composition.html)
 - [Association](https://www.uml-diagrams.org/association.html)
 - [Aggregation](https://www.uml-diagrams.org/aggregation.html)
 - [Generalization](https://www.uml-diagrams.org/generalization.html)
 - [Specialization](https://www.indeed.com/career-advice/career-development/generalization-vs-specialization)
 - [Dependency](https://www.uml-diagrams.org/dependency.html)
 - [Realization](https://www.uml-diagrams.org/realization.html)

### Concepts
 - [Encapsulation](https://www.tutorialspoint.com/csharp/csharp_encapsulation.htm)
 - [Reflection](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/reflection)
 - Polymorphism
    - [Overloading](https://docs.microsoft.com/en-us/dotnet/standard/design-guidelines/member-overloading)
    - [Overriding](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/knowing-when-to-use-override-and-new-keywords)
    - [Generics](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/types/generics)
 - [Persistence](https://en.m.wikipedia.org/wiki/Persistence_(computer_science))
 - [Modularity](https://codewithmukesh.com/blog/modular-architecture-in-aspnet-core/)
 - [Decoupling](https://intellitect.com/blog/decoupling-csharp-testable/)

### S.O.L.I.D Design Principles
 - [Single Responsibility Principle](https://dev.to/tamerlang/understanding-solid-principles-single-responsibility-principle-523j)
 - [Open/Closed Principle](https://dev.to/tamerlang/understanding-solid-principles-open-closed-principle-5e25)
 - [Liskov Substitution Principle](https://dev.to/tamerlang/understanding-solid-principles-liskov-substitution-principle-46an)
 - [Interface Segregation](https://dev.to/tamerlang/understanding-solid-principles-interface-separation-32ck)
 - [Dependency Inversion Principle](https://dev.to/tamerlang/understanding-solid-principles-dependency-inversion-1b0f)

### General Responsibility Assignment Software Patterns ([GRASP](http://www.kamilgrzybek.com/design/grasp-explained/))
 - Information Expert
 - Creator
 - Indirection
 - Low Coupling
 - High Cohesion
 - Polymorphism
 - Protected Variations
 - Pure Fabrication
 - Controller

### Gang of Four ([GOF](https://springframework.guru/gang-of-four-design-patterns/))
 - Creational Design Patterns
   - Abstract Factory. Allows the creation of objects without specifying their concrete type.
   - Builder. Uses to create complex objects.
   - Factory Method. Creates objects without specifying the exact class to create.
   - Prototype. Creates a new object from an existing object.
   - Singleton. Ensures only one instance of an object is created.
 - Structural Design Patterns
   - Adapter. Allows for two incompatible classes to work together by wrapping an interface around one of the existing classes.
   - Bridge. Decouples an abstraction so two classes can vary independently.
   - Composite. Takes a group of objects into a single object.
   - Decorator. Allows for an object’s behavior to be extended dynamically at run time.
   - Facade. Provides a simple interface to a more complex underlying object.
   - Flyweight. Reduces the cost of complex object models.
   - Proxy. Provides a placeholder interface to an underlying object to control access, reduce cost, or reduce complexity.
 - Behavior Design Patterns
   - Chain of Responsibility. Delegates commands to a chain of processing objects.
   - Command. Creates objects which encapsulate actions and parameters.
   - Interpreter. Implements a specialized language.
   - Iterator. Accesses the elements of an object sequentially without exposing its underlying representation.
   - Mediator. Allows loose coupling between classes by being the only class that has detailed knowledge of their methods.
   - Memento. Provides the ability to restore an object to its previous state.
   - Observer. Is a publish/subscribe pattern which allows a number of observer objects to see an event.
   - State. Allows an object to alter its behavior when its internal state changes.
   - Strategy. Allows one of a family of algorithms to be selected on-the-fly at run-time.
   - Template Method. Defines the skeleton of an algorithm as an abstract class, allowing its sub-classes to provide concrete behavior.
   - Visitor. Separates an algorithm from an object structure by moving the hierarchy of methods into one object.

### Miscellaneous Principles
 - [Invertion of Control](https://en.m.wikipedia.org/wiki/Inversion_of_control)
 - [Separation of Concerns](https://en.m.wikipedia.org/wiki/Separation_of_concerns)
 - [SLAP](https://dzone.com/articles/slap-your-methods-and-dont-make-me-think) (Single Level of Abstraction Principle)
 - [LBYL](https://realpython.com/python-lbyl-vs-eafp/) (Look Before You Leap) <sub><sup>// mostly related to python</sup></sub>
 - [EAFP](https://realpython.com/python-lbyl-vs-eafp/) (it's Easier to Ask Forgiveness than Permission) <sub><sup>// mostly related to python</sup></sub>
 - [DRY](https://thevaluable.dev/dry-principle-cost-benefit-example/) (Don’t Repeat Yourself)
 - [WET](https://betterprogramming.pub/when-dry-doesnt-work-go-wet-6befda0444bf) (Write Everything Twice)
 - [AHA](https://kentcdodds.com/blog/aha-programming) (Avoid Hasty Abstractions)
 - [KISS](https://www.freecodecamp.org/news/keep-it-simple-stupid-how-to-use-the-kiss-principle-in-design/) (Keep It Simple, Stupid)
 - [YAGNI](https://martinfowler.com/bliki/Yagni.html) (You Aren’t Gonna Need It)
 - [RTFM](https://www.computerhope.com/jargon/r/rtfm.htm) (Read The Fucking Manual) 
 - [JFGI](https://www.urbandictionary.com/define.php?term=jfgi) (Just Fucking Google It) <sub><sup>// not really a principle</sup></sub>

### Data Structures & Algorithms
 - Levenshtein distance algorithm 

### Programming Models
 - Object Oriented Programming (OOP)
 - Functional Programming
 
### Architectural Patterns
 - Model-View-ViewModel (MVVM)
 - Model-View-Controller (MVC)
 - Model-View-Presenter (MVP)

### API Architectural Patterns
 - GraphQL
 - Representational State Transfer (REST)
 - Remote Procedure Call (gRPC)
 - Simple Object Access Protocol (SOAP)

### Development Process
 - Test Driven Development (TDD)
 - Behavior Driven Development (BDD)
 - Domain Driven Development (DDD)
 - [Responsibility Driven Design](https://www.wirfs-brock.com/PDFs/A_Brief-Tour-of-RDD.pdf) 
 - Clean Architecture

### Anti-Patterns & Code Smells
 - Anemic Domain Model
 - Golden Hammer
 - Boat Anchor
 - Dead Code
 - God Objects
 - Shotgun Surgery
 - Middle Man
 - Speculative Generality
 - Spaghetti Code
 - Inner-Platform Effect

### Project Management
 - Agile Model
   - Scrum
     - [Stakeholder Management](https://www.scrum.org/resources/blog/10-tips-product-owners-stakeholder-management)
     - [Risk Management](https://www.scrum.org/resources/blog/managing-risk-scrum)
   - Kanban
     - Visualize Workflow 
     - Limit Work in Progress (WIP) 
     - Focus on Flow
     - Continuous Improvement
   - [Extreme Programming](https://www.agilealliance.org/glossary/xp/)
 - Waterfall Model
 - [Salience Model](https://pmstudycircle.com/salience-model-to-analyze-project-stakeholders/)

### [User Stories](https://xp123.com/articles/invest-in-good-stories-and-smart-tasks/)
 - INVEST
   - Independent
   - Negotiable
   - Valuable
   - Estimable
   - Small
   - Testable
 - SMART
   - Specific
   - Measurable
   - Achievable
   - Relevant
   - Time-boxed 

### Design Pattern:
 - Creational
 - Behavioral
 - Structural 

### Best Practices
 - Pascal casing, camel casing
 - Folder/Project structure
 - Triple A (UnitTesting)

### Buzzwords <sub><sup><sup>kinda makes me sound cool</sup></sup></sub>
 - Artificial Intelligence (AI)
 - Machine Learning (ML)
 - Optical Character Recognition (OCR)
 - Non-Fungible Token (NFT)
 - Big Data
 - Blockchain
 - Metaverse
 - Microservices

### Advice
 - [Make it work, Make it Right, Make it fast](https://betterprogramming.pub/the-principles-of-software-development-7415e7c5a156)

### Useful Resources
 - [Refactoring Guru](https://refactoring.guru/)
 - [Martin Fowler](https://martinfowler.com/)
 - [Uncle Bob](http://cleancoder.com/products)
 - [Try QA](http://tryqa.com/)
 - [Scrum Guides](https://scrumguides.org/)

### Articles & Blogs
 - [Saying No to Stakeholders](https://www.mountaingoatsoftware.com/blog/six-guidelines-for-saying-no-to-a-stakeholder)
 - [Stakeholder Management](https://www.pmi.org/learning/library/stakeholder-management-task-project-success-7736)
 - [10 Principles of Stakeholder Engagement](https://www.henricodolfing.com/2018/03/10-principles-of-stakeholder-engagement.html)
 - [10 Tips for Product Owners](https://www.scrum.org/resources/blog/10-tips-product-owners-stakeholder-management)

### Misc
 - Line of Business
 - Business Domain

<!-- Written and Directed by ToxicK1dd - https://baek.pro/ -->
