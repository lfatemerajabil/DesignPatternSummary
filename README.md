# DesignPatternSummary
`*patterns are not algorithms because they are different in two different problems and the patterns don’t give exact order of complexity and it is up to you.*`

## The parts of a pattern:
- intent
- motivation
- structure
- code example
- applicability
- implementation
- relations with other patterns

*3 types of patterns based on intent:*
- creational
- structural
- behavioral

## Creational:
1. factory method: we want to create some objects. so we use two classes as creator and product and subclasses for them.

2. abstract factory: sometimes we want to create objects don’t care about some segmentation of the objects. 

3. builder: complex object and similar to abstract factory but is step by step for creating an object

4. Prototype: copy with copy.copy(an object) with function - - copy - - in class of object.

5. Singelton: we can have one and only one object from a class. we can use a private variable or use if condition in the main method.

## Structural
1. Adapter: relation between different objects like JSON and XML in output.

2. Facade: relation between a complex subsystem and a new class. use a new class and some methods related to other classes.

3. Bridge: separate two classes with the definition of a father class.

4. Decorator: we use a class as a father of two classes. one for object and another for decorator of it with the overriding method.
for example, we have a database file, so we must have a class for main data and a class for decorating data, and a class for father of both these. for another example suppose a coffee and its some types of drink and we can add on them something like milk and sugar.

5. Proxy: for a better answer to the queries and list them. like a social network where needs a proxy for working faster.

## Behavioral
1.strategy: different algorithms are subclasses of a strategy class and the main class have the conditions for different situation 

2. Observer: one to many. this pattern lets us notify changes in an object to some of the connected objects, not all of them. like a store and its customers

3. State: a pattern for implementing different states and move between them for an object. this movement is called transmission. so instead of the switch-case method, we use an interface for state and subclasses of it that show different states and we have a separate class for our object.
for example, a player in a game is an object and ready, locked, playing are different states.

4. Command: this pattern is for when you want to schedule and queue operations because you have a stand-alone object that you have all information and you request to it. so you have an interface for command and some subclasses for different commands.
for example, you have an editor class with different buttons like copy, paste, cut, undo, and history that are your commands

5. Visitor: when you want to perform an operation for your complex object that has some elements. so you must have your complex object class and its subclasses and a visitor class related to your subclasses by some methods and you have more than one visitor so you have some subclasses for your visitor class.
for example, a shape class and its children are rectangular, circle, … and you want to know their coordination and their areas.

(My reference is [Here])(https://refactoring.guru/design-patterns/python/)
Share your comment about this repo
