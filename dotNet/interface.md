# Interface
I’ll summarise what I read in a Quiz form.

### What is an interface?
-	It a collection of definitions for a set of related functionalities.


### Why do we use interfaces?
-	Interfaces allow us to use multiple inheritance.

### What about an interface’s implementation?
-	An interface’s implementation must be provided by a class or a struct and this implementation must be for all the methods inside that interface.

### Can an interface have a static method?
-	Yes. It may have a static method.

### How can we define an interface?
-	By using the interface keyword.


### Can an interface be a member in any way?
-	Yes, it can be a member of a class or a namespace.

### What declaration can an interface have?
-	It can have declarations but without implementation for methods, properties, indexers and events.


### Can an interface member have a body?
-  Well, actually it can have something called a default implementation. This implementation can be provided for classes and structs that don’t have an overriding implementation.

### What can an interface include?
-	It can include constants, operators, static constructor, and nested types.

### Give an example for something an interface cannot contain?
-	An interface cannot have an instance state.

### What is the explicit interface implementation?
-	When you explicitly tell the compiler that a particular member belongs a particular interface.

### When is it a must to use the explicit interface implementation?
-	It is a must to use it when an interface inherits more than one base interface and that interface overrides a method that is implemented in a base interface.











