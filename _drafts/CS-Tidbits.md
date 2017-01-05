---
layout: post
title: CS Tidbits I've Been Picking Up
---
Most of the definitions are copied from Wikipedia.


* **Call Stack**  
A stack data structure that stores information about the active subroutines of a computer program.  A call stack is composed of *stack frames* (also called activation records or activation frames).
* **Stack Trace** or **Traceback**  
A report of the active stack frames at a certain point in time during the execution of a program - i.e., a snapshot of the call stack 
* **Protocol**
a common means for unrelated objects to communicate with each other; definitions of methods and values which the objects agree upon in order to co-operate. Python does not have specific language/syntax for protocols, but other languages do (e.g. Java interfaces).
* **Multi-Inheritance**
A feature of some object-oriented computer programming languages in which an object or class can inherit characteristics and features from more than one parent object or parent class. It is distinct from single inheritance, where an object or class may only inherit from one particular object or class.
* **Diamond Problem**
An ambiguity that arises when two classes B and C inherit from A, and class D inherits from both B and C. If there is a method in A that B and C have overridden, and D does not override it, then which version of the method does D inherit: that of B, or that of C?  It only occurs when multi-inheritance is allowed.  Python mitigates this problem with an order of inheritance determined by the C3 linearization algorithm.
* **Aliasing**  
A situation in which a data location in memory can be accessed through different symbolic names in the program. Thus, modifying the data through one name implicitly modifies the values associated with all aliased names.
* **Scope**  
In computer programming, the scope of a name binding – an association of a name to an entity, such as a variable – is the part of a computer program where the binding is valid: where the name can be used to refer to the entity.  The scope of a binding is also known as the visibility of an entity. A scope is a part of a program that is or can be the scope for a set of bindings… in casual use and in practice largely corresponds to a block, a function, or a file, depending on language and type of entity.
  * Dynamic scoping
    * name resolution depends upon the program state when the name is encountered which is determined by the execution/calling context
    * variable's definition is resolved by searching the calling function, then the function which called that calling function, and so on, progressing up the call stack
    * can only be determined at run time
  * Lexical/static scoping
    * name resolution depends on the location in the source code, which is defined by where the named variable is defined
    * variable's definition is resolved by searching its containing block or function, then if that fails searching the outer containing block, and so on
    * can be determined at compile time
* **Syntactic Sugar**  
Syntax within a programming language that is designed to make things easier to read or to express. It makes the language "sweeter" for human use: things can be expressed more clearly, more concisely, or in an alternative style that some may prefer.  
Specifically, a construct in a language is called syntactic sugar if it can be removed from the language without any effect on what the language can do: functionality and expressive power will remain the same.  
Examples from Python: decorators, list comprehension, accessing matrix elements by index
*  **Decorators**
Function decorators are wrappers to existing functions.  They dynamically alter the functionality of a function, method or class without having to directly use subclasses. 
*  **Annotations**  
like decorators for java programs!
preceded by the at sign (@) - @ = AT, as in annotation type
* **Race Condition**  
The behavior of an electronic, software or other system where the output is dependent on the sequence or timing of other uncontrollable events. It becomes a bug when events do not happen in the order the programmer intended. The term originates with the idea of two signals racing each other to influence the output first.
* **Polymorphism**  
In English, polymorphism is the condition of occurring in several different forms.  
In computer science, polymorphism is the provision of a single interface to entities of different types.  It comes in several flavors:  
  - *ad hoc polymorphism*:
  function overloading
  - *parametric polymorphism*:
  generic programming
  - *subtyping*:
  when a name denotes instances of many different classes related by some common superclass

