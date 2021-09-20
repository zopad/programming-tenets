+++
title = "Single Responsibility Principle (SRP)"
date = 2021-09-20T02:13:50Z
author = "Anon"
categories = [
    "Development"
]
tags = [
    "development"
]
+++

## Introduction

The single responsibility principle says that every class or module in a program should only provide one specific functionality. As Robert C. Martin puts it, "A class should have only one reason to change."

Classes and modules often start off this way. Be careful not to add too many responsibilities as classes get more complicated. Refactor and break them up into smaller classes and modules.

The consequence of overloading classes is twofold. First, it complicates debugging when you're trying to isolate a certain module for troubleshooting. Second, it becomes more difficult to create additional functionality for a specific module. 

```
## this is a comment
$ echo this is a command
this is a command
```


### Don't Repeat Yourself

DRY is a good design goal and Hugo does a great job supporting it. Part of the art of a good template is knowing when to add a new template and when to update an existing one. While you're figuring that out, accept that you'll be doing some refactoring. Hugo makes that easy and fast, so it's okay to delay splitting up a template.