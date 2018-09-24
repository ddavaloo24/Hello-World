# Java
Java is an object-oriented programming language and a platform developed by Sun Microsystems (eaten by Oracle). It uses the WORA principle which is write once, run anywhere, meaning a Java app can be executed on any platform with a JVM. It's a flexible and popular language for many years allowing developers to write client-server web applications, desktop and mobile apps, and frameworks and libraries.

## Features
**Platform independence** The compiler converts source code to byte code and the JVM executes that bytecode. While each OS has their own "JVM", so every JVM can execute bytecode regardless of origin.

**Clear verbose syntax** Java has C-like syntax, many syntax elements of the language are readable and widely used in programming. The Java API (application programming interface) is also written using verbose naming conventions making it simple to parse large code bases.

**Multiparadigm** While Java is OOP, it supports multiple paradigms such as imperative, generic, concurrent, and functional.

**Garbage collection** The JVM performs automatic memory deallocation of unused objects at runtime. Programs are written without the need for complex mem management. 

**Multithreading** Java supports multithreading at both the language and the standard library levels. It allows concurrent and paraller execution of several parts of a java program.

**Object oriented programming** Although Java accomodataes several paradigms, OOP is the foundation for most applications. I OOp, a program is organized into objects encapsulating related fields and methods. When defining objects, Java reserves the keyword "class" which serves ass their blueprint. An object in Java represents an instance in memory of a class, and also every class implicity inherits  from the Object superclass, which provides useful conveniece methods like equals and toString. Java popularized several 'Pillars of OOP' design theory. While the numbers vary between OOP, Java focuses on 4:

*Abstraction* By simplifying objects to a set of useful features, we hide irrevelant details, reduce complexity, and increase efficiency. Absraction is important at all levels of software and computer engineering, but essential to desgning useful objects. Complicated stuff are reduced to simple versions.

*Encapsulation* Objects should group related groups and functions and be in complete control over them. So the state of an objec, if ever, through the object itself AKA data hiding because the object has sole responsibility for its fields and no outside object or function should interfere.

*Inheritance* Code reuse is important in programming and new classes can use code from existing ones. It establishes a superclass-subclass relationship where the derived classes inherit and sometimes change fields and methods from its parent. 

*Polymorphism* With inheritance, an object of a derived class can be referenced as instances of its parent class. This provides flexibility when invoking ingerited methods with varying implementations in derived classes. 