---
layout: pattern
title: Dependency Injection
folder: dependency-injection
permalink: /patterns/dependency-injection/
categories: Behavioral
tags:
 - Java
 - Difficulty-Beginner
---

## Intent
Dependency Injection is a software design pattern in which one or
more dependencies (or services) are injected, or passed by reference, into a
dependent object (or client) and are made part of (一部分)the client's state. The
pattern separates the creation of a client's dependencies from its own
behavior, which allows program designs to be loosely coupled (松耦合)and to follow the
inversion of control (控制反转)and single responsibility principles(单一原则).

![alt text](./etc/dependency-injection.png "Dependency Injection")

## Applicability
Use the Dependency Injection pattern when

* when you need to remove knowledge of concrete(具体) implementation from object
* to enable unit testing of classes in isolation using mock objects or stubs
