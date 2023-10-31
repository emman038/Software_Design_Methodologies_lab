#Software Design Methodologies
&nbsp;  
## What do we mean by coupling and cohesion when discussing structured design?

Structured design dictates that modules are well organized in order to achieve a precise solution. **Coupling** and **Cohesion** refer to the ways these modules communicate:

1. **High Cohesion** 
This refers to how elements of a module belong together. In the context of structured design the aim is to have high cohesion. What this means in practical sense is that elements in modules of systems are closely related to each other and work together to perform a single, well-defined task.
	- Modules are only made up of elements that allow it to be able to perform its specific functionality.
	- Closely related elements are grouped together in a module, modules then make up systems.

2. **Low Coupling** - This refers to how much different modules of a system rely on each other for the system to work. In the context of Structured design, the aim is to have modules that have low coupling. 
	- Modules should be loosely coupled so that each module can be modified or replaced with minimal impact on other modules in the system.

##What is the difference between top-down and bottom-up design? 
Top-down approach starts with the bigger picture in mind, with a high-level overview of the software requirements. Systems are then broken down into modules/sub-systems and further refined and abstracted till they can be easily modified/implemented.

In contrast, Bottom-Up approach starts with building the sub-systems/modules and assembling them into larger modules. These modules are then combined to form systems.

Top-down designs are typically more adaptable to changes made in software requirements whereas bottom-up designs can be less adaptable to changes in software requirements.

## Which best describes a function oriented design?

Top-down approach best describes a function oriented design. This is because an high level overview is taken and there is a clear overall structure. The purpose of function oriented design is to break systems down into functions and a top-down approach allows you to be to achieve this.

## What are the four pillars of object oriented programming? Give a single-sentence description of each.

1. **Data abstraction** - Hiding unnecessary details/information about an object's internal structure, focusing instead on the essential properties and behaviours.
2. **Encapsulation** - Preventing unauthorized access and modification of data by removing access to parts of the codebase and making some code private to certain code blocks.
3. **Inheritance** - Ability to create child classes that inherit properties and methods from an existing  existing parent class.
4. **Polymorphism** - Ability to create objects that form part of the same superclass due to the objects containing the same methods.

## What is the strategy pattern? How would its implementation differ between a functional and object oriented system?

**Strategy Pattern** is a type of behavioural pattern where a class behaviour or its algorithim can be changed at runtime. Different objects that represent different strategies are created and a context object that would represent one of the strategy objects.

In object-oriented design - Interfaces are used to achieve Strategy Patterns

In function-oriented design - Functions take in other functions as parameters and return functions as a result of calling functions

##Imagine your is creating a new online payment system. In order to gain maximum market share it can't be tied to a particular sector - it needs to work just as well when ordering a takeaway as when buying a new coat. Which design methodology would you suggest following? Give some justification for your decision. 

I would use the **Object oriented design** methodology. My justification for using this metholody is that I can utilise design patterns such as **implement to interface** which will allow me to create classes that contain interchangable methods.