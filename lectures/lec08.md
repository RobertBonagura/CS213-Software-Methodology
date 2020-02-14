2-14-20
# Lecture 8 - Class Diagrams
## UML Classes
Classes ar represented by rectangles which wither bear only the anme of teh class in bold, or show attributes and operations as well.

Attributes and operations are listed at least with their names.

#### Visibility modifiers:
+public<br>
#protected<br>
-private<br>

## Associations
Dependencies and Generalizations represent difference level of importance or difference level of abstraction.

Association is a structural relationship that specified that objects of one thing are connected to objects of another.

Associataions may be annotated with information taht describes the association.

### Multiplicity
Specifies the number of objects of the opposite class to which an object can be associated.
* Cardinality - number of elements
* Mulitplicity - range of allowed cardinalities

### Dependencies
A "using" relationship.

A change in specification of one thing may affect another thing that uses it.
* For example, one class uses another calss as as argument in the signature of an aoperation.

### Generalization
A relationship between a general thing (superclass) and a more specific kind of that thing (subclass)

IT is a "is-a-kind-of" relationship, for example: rectangle is a kind of square.

**Generalization** in the UML is implemented as **inheritance** in OO programming.

---
In class example using exercise 4.1

---

## Exception Handling
Just begun foing over Exeption Handling Notes