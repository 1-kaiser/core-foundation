# Software Design Patterns

Software design patterns are **proven, reusable solutions to common problems** in software architecture and development.  
They provide a shared vocabulary and best practices for building **maintainable, flexible, and scalable** applications.  

---

## Categories of Design Patterns

### 1. Creational Patterns
Focus on **object creation mechanisms**. They abstract the instantiation process, making systems more flexible in deciding what to create.

- **Singleton** → Ensure a class has only one instance (e.g., configuration, logging).  
- **Factory Method** → Define an interface for creating objects, but let subclasses decide which class to instantiate.  
- **Abstract Factory** → Create families of related objects without specifying concrete classes.  
- **Builder** → Step-by-step creation of complex objects.  
- **Prototype** → Create new objects by cloning existing ones.  

**Resources:**
- [Singleton](https://refactoring.guru/design-patterns/singleton)  
- [Factory Method](https://refactoring.guru/design-patterns/factory-method)
- [Abstract Factory](https://refactoring.guru/design-patterns/abstract-factory)
- [Builder](https://refactoring.guru/design-patterns/builder)
- [Prototype](https://refactoring.guru/design-patterns/prototype)

---

### 2. Structural Patterns
Deal with **object composition** and how classes and objects work together to form larger structures.

- **Adapter** → Make incompatible interfaces work together.  
- **Bridge** → Separate abstraction from implementation for independent development.  
- **Composite** → Treat individual objects and compositions uniformly (e.g., UI hierarchies).  
- **Decorator** → Dynamically add responsibilities to objects.  
- **Facade** → Provide a simplified interface to a complex system.  
- **Proxy** → Control access to an object (e.g., lazy loading, security).  

**Resources:**
- [Adapter](https://refactoring.guru/design-patterns/adapter)  
- [Bridge](https://refactoring.guru/design-patterns/bridge)
- [Composite](https://refactoring.guru/design-patterns/composite)
- [Decorator](https://refactoring.guru/design-patterns/decorator)
- [Facade](https://refactoring.guru/design-patterns/facade)
- [Proxy](https://refactoring.guru/design-patterns/proxy)

---

### 3. Behavioral Patterns
Focus on **object interaction and responsibility delegation**.

- **Observer** → Define a one-to-many dependency (e.g., event listeners).  
- **Strategy** → Define a family of algorithms, encapsulate them, and make them interchangeable.  
- **Command** → Encapsulate requests as objects, enabling undo/redo.  
- **State** → Allow an object to alter its behavior when its internal state changes.  
- **Mediator** → Reduce coupling by having a mediator handle interactions.  
- **Iterator** → Provide a standard way to access elements of a collection.  
- **Chain of Responsibility** → Pass requests along a chain of handlers.  

**Resources:**
- [Observer](https://refactoring.guru/design-patterns/observer)  
- [Strategy](https://refactoring.guru/design-patterns/strategy)
- [Command](https://refactoring.guru/design-patterns/command)
- [State](https://refactoring.guru/design-patterns/state)
- [Mediator](https://refactoring.guru/design-patterns/mediator)
- [Iterator](https://refactoring.guru/design-patterns/iterator)
- [Chain of Responsibility](https://refactoring.guru/design-patterns/chain-of-responsibility)

---

[Code examples here](https://refactoring.guru/design-patterns/examples)

---
