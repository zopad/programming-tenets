+++
title = "Interface segregation principle"
description = "The weakest of the big 5"
author = "Anon"
tags = [
    "development"
]
date = 2021-09-20T02:13:54Z
categories = [
    "Development"
]
# menu = "main"
+++

## In short
Many client-specific interfaces are better than one general-purpose interface.

## Detailed
The interface-segregation principle (ISP) states that no client should be forced to depend on methods it does not use.
ISP splits interfaces that are very large into smaller and more specific ones so that clients will only have to know about the methods that are of interest to them.
Such shrunken interfaces are also called role interfaces.
ISP is intended to keep a system decoupled and thus easier to refactor, change, and redeploy.