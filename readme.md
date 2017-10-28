# Intro
- These are notes from the Lynda course on SOLID
- You'll find examples each principle under it's subdirectory
- SOLID is more of a guideline than a rigid methodology

## SOLID DEFINED
- Single Responsibility
    - Summarizes all four principles below
    - When these four are implemented, the class should only have one responsiblitiy
    - 
- Open for extension, Closed for modification
    - Helps tune the design
    - Helps decide which features of a class need to be exposed
- Liskov Substitution
    - Objects of superclass S can be replaced with objects of any subclass of S
    - Suggests that subclasses must be able to replace parent classes.
    - Aids in polymorphic design
- Interface Segregation
    - Helps to drive good class design
    - Helps when writing unit tests
- Dependency Inversion
    - Focused on packaging code
    - Depend on abstract classes or interfaces
    - Avoid concrete class name dependencies

## Other Principles
- DRY: Don't repeat yourself
- GRASP: General Responsibility Assignment Software Principles
    - Helps define the Single in _S_OLID in a meaningful way
- TDD: Test driven development

## Why Use Solid?
- Helps to identify problem code
- Helps design better code
- 