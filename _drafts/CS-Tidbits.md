---
layout: post
title: CS Tidbits I've Been Picking Up
---

* **Try/Catch**
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
Examples: decorators, list comprehension, accessing matrix elements by index
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

