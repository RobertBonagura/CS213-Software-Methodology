2-7-20
# Lecture 6 - Polymorphism,  Abstract Classes and Interfaces
Spent time Reviewing Program 1 assignment sheet.

## Dynamic Binding
Important to understand when you have a hierarchy of subclasses.

Liskov Substituition Principle (LSP)
1. A child can be used wherever a parent is expected; child class must be completely substitutable for their parent class.
2. For every overriing method in a child ...
3. 

## instanceof Operator

## Protected Data and Methods
The `final` keyword

## Abstract Classes
Used to define common behavior for classes, without giving implementation.

Used when you want to enforce a certain type of behavior, yet you dont want to define how it will be implemented. If you extend an abstract class, you are then required to implement all abstract methods.

Uses `abstract ` keyword. 

Cannot be used to instantitate an object.<br>
However, they can be used as a data type.

## Interfaces
Java does not allow multiple inheritance. A workaround for this is java interfaces. Works the same way as a super class, only in a java interface class, it only has abstract methods. You can implemenent multiple inheritances.