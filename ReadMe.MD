[![Build Status](https://travis-ci.org/kaw393939/is219hello.svg?branch=master)](https://travis-ci.org/kaw393939/is219hello)


To start with, let's give you a simplistic, high-level view of what Object-oriented programming (OOP) is. We say simplistic, OOP can immediately get very complex, and giving it a full treatment now would reasonably confuse more than help. The basic idea of OOP is that we use objects to model real-world things that we want to represent inside our programs, and/or provide a simple way to access functionality that would contrarily be hard or impossible to make use of.

Objects can include related data and code, which represent knowledge about the thing you are trying to model, and functionality that you want it to have. Object data can be stored easily (encapsulated) inside an object package, making it easy to structure and access; objects are also usually used as data stores that can be easily sent across the network.

From a class, we can create object instances — objects that contain the data and functionality defined in the class. From a Person class, we can now create some actual people:
Class Person:
Name, Gender, Age..etc.

When an object instance is generated from a class, the class's constructor function is run to create it. This process of creating an object instance from a class is called instantiation — the object instance is instantiated from the class.

JavaScript uses specific functions called constructor functions to establish and initialize objects and their features. They are useful because you'll often come across situations in which you don't know how many objects you will be instantiating; constructors provide the means to create as many objects as you need efficiently, attaching data and functions to them as required.
