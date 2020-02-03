1-31-20
# Lecture 4 - Object-Oriented Design

## Mutable vs Immutable
Immutable means that the object can not be changed.

A class with private data fields, has no setters, but does have a getter is then mutable. A reference to the object is all you need for it to be mutable.

## Class Abstractions and Encapsulation
Class abstraction is seperation of class implementation from the use of a class.

It is like a contract between your program and a client. Is a promise to provide some type of service (through methods). These classes are known as **Abstract Data Types** (ADT). 

## Stepwise Refinement
Begin by using method abstraction to isolate details from design and only later implement the details.

Breaking large problems into multiple, small, manageable problems, each subproblem implemented using a single method.

## Class Relationships
Common relationships among classes are association, aggregation, composition and inheritance:
* Association
    * A general binary relationship that describes that there is some type of activity (method calling) between the two classes.
    * **Mulitplicity** can be used to define upper and lower bound of number of entitites that can participate in the activity.
* Aggregation and Composition
    * **Aggregation** is a form of association that representes an ownership relationship between two objects.
    * **Composition** is a strict form of aggregation, implying exclusive ownership.
        * If a class A has strict ownership of class B, then if A is deleted so will be B.

There are some examples to refer to:
* Designing the Course Class
* Desgining the Stack Class

You want to minimize **coupling** or, *messy association lines*, so that design is not too complicated and so that classes can easily be removed or added without comprimising the design.

## Processing Primitive Data Type Values as Objects
Package **java.lang** provides a wrapper for primitive data types to allow them to be passed by reference to an Object.

#### Boxing and autoboxing and autounboxing
Wrapping the primitive data type as an object is boxing.

String is immutable - once created you can not change the value.<br>
A char array can be used to instantitate a String object.<br>
String literals can also be assigned String variables.

String literals will compare by === as true. Though objects instatiated will not. This is because repeated string literals will be saved in the same location. An object instantiated with `new` will always be stored in a new address.

StringBuilder allows us to handle more complicated features with String.

## Inheritance
1. Reuse common features
2. Extend functionality (with change in software)

### Superclasses and Subclasses
Implementation of generalization of common properties and behaviors of a class.

A subclass is used to introduce a new property or behavior.

Java enforces single inheritance - no multiple inheritance (The way around this is java Interfaces)

In Generalization, white triangle points to superclass