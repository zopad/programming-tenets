+++
title = "Liskov Substitution Principle"
description = ""
date = 2021-09-20T02:13:53Z
author = "Anon"
categories = [
    "Development"
]
tags = [
    "development"
]
+++

## Introduction
 "Functions that use pointers or references to base classes must be able to use objects of derived classes without knowing it."

## Full definition

Substitutability is a principle in object-oriented programming stating that, in a computer program, if S is a subtype of T, then objects of type T may be replaced with objects of type S (i.e., an object of type T may be substituted with any object of a subtype S) without altering any of the desirable properties of the program (correctness, task performed, etc.).
More formally, the Liskov substitution principle (LSP) is a particular definition of a subtyping relation, called (strong) behavioral subtyping, that was initially introduced by Barbara Liskov in a 1988 conference keynote address titled Data abstraction and hierarchy.
It is a semantic rather than merely syntactic relation, because it intends to guarantee semantic interoperability of types in a hierarchy, object types in particular.