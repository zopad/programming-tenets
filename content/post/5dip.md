+++
title = "Dependency Inversion Principle (DIP)"
author = "Anon"
date = 2021-09-20T02:13:55Z
categories = [
    "Development"
]
tags = [
    "development"
]
+++

## In short
 "Depend upon abstractions, not concretions."

## Full definition
In object-oriented design, the dependency inversion principle is a specific form of loosely coupling software modules. When following this principle, the conventional dependency relationships established from high-level, policy-setting modules to low-level, dependency modules are reversed, thus rendering high-level modules independent of the low-level module implementation details. The principle states:

* High-level modules should not import anything from low-level modules. Both should depend on abstractions (e.g., interfaces).
* Abstractions should not depend on details. Details (concrete implementations) should depend on abstractions.

By dictating that both high-level and low-level objects must depend on the same abstraction, this design principle inverts the way some people may think about object-oriented programming.

The idea behind points A and B of this principle is that when designing the interaction between a high-level module and a low-level one, the interaction should be thought of as an abstract interaction between them. This not only has implications on the design of the high-level module, but also on the low-level one: the low-level one should be designed with the interaction in mind and it may be necessary to change its usage interface.

In many cases, thinking about the interaction in itself as an abstract concept allows the coupling of the components to be reduced without introducing additional coding patterns, allowing only a lighter and less implementation-dependent interaction schema.

When the discovered abstract interaction schemas between two modules are generic and generalization makes sense, this design principle also leads to the following dependency inversion coding pattern. 