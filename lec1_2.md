# Introduction
(Lectures 1 and 2)
## Methods for developing good software

* Maintainabiliity
* Dependability and Security
* Efficiency
* Usability and Acceptability

## 5 Major Activities in software development
* Requirement Analysis / Specification
* Design (UML, diagrams)
* Implementation
* Verification and Validation
* Delivery / Maintenance / Evolution

## Software Process Models
There are multiple process models for software - the two most prominent being Waterfall and Agile.
* Waterfall - where each activity in the software development process is not started until it's previous activity is completed
    * leads to longer period between releases
* Agile 
    * Allows more involvement from customer in the dev process.
    * More frequent releases of software

[Agile 101 Map](https://www.agilealliance.org/agile101/subway-map-to-agile-practices/)

---

## Programming Ground Rules
Includes 'clean code', modularity, meanigful names and purposeful comments among some other guidelines. For more information open [Ground Rules](file:///Users/robert.bonagura/Desktop/Software/213rules.htm) in live server to review guidelines

Javadoc - can autogenerate documentation when writing methods
    
    /**
    This is a concise summary of method.
    May contain more senteces to elaborate.
    @param paramname    comment on pararmater
    @return    return value is commented here
    */
    
* Comment block on top of each class.
* Each class gets its own java file.
* Use thoughtful names (variables, methods, classes).
* No magic numbers. 

# Object-Oriented Software Development
In traditional programming, the key abstraction is a function/process/procedure. In OO design, the key abstraction is the object itself. 

Class diagram are used to represent an object and it's relation to 
other objects.

## Characteristics of OOD
Objects are abstractions of real world entities, encapsulating data and
processes.
    
### Advantages of OOD
Reusability through inheritance.<br>
Extendability by creating new subclasses with new behaviors.<br>
Data hidden by exapsulation (Make data private, and only accessible with public methods).<br>
Easier to maintain (when using good design and modularity).




