2-5-20
# Lecture 5 - Inheritance and Polymorphism
**Inheritance** - The implementation of gerneralization in class diagram.

Allows you to:
* Reuse code
* Extend some functionality
* Change behaviors
* Indirect access
    * data fields are private, with getter methods accessing the data fields

## Overriding Methods
A subclass inherits methods from a duperclass, and so somethimes ti is neccsary for the suvlcass to modify the implementation of some methods (such as a toString method or a equals() method.)


## Overriding vs Overloading
Overriding means to provide a new implementation for a method in the sublclass.

Overloading means to define multiple methods with the same name, but different signatures within the same class.
* This is a result of **dynamic binding** which we will revisit later.

## Polymorphism

Creating one instance each of parent and child class.

Remember a child class is always an instance of a parent class.
* When type-casting, can only cast child to parent. Not parent to child.

### Run-Time Binding
If you cast child to parent class reference, and then call a .show() method, you will still call the child class method.
* In this case, the *actual-type* differs from the reference type.
* At compile time, yes b is a parent, but at a compile time is it is a child class

