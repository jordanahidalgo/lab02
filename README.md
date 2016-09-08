# Lab 02 -- Chapter 01

## Define the followint terms:
*Object: State or behavior (instance) of a class.
*Class: Blueprint (code) that defines how to create an object.
*Instance: A specific realization of any object.
*Method: A collection of statements used to manipulate (mutators) or access (accessors) information from an object of that class. (Behaves like a function in mathematics).
*Signature: Name of the method and the type of parameter i.e. the following signature changes the size of the instance `box` of class `Box` and does not give an output. I.e. the following string below.
```
void changeSize(Box box)
```
*Parameter: An input of the method. I.e. `box` is the parameter in the example above.
*Type: Defines what values the parameter is allowed to be. I.e. `method (int x);` can only be a whole number because it is defined by type int which is only a whole number
*State: Set of values describing/defining an object. The attributes of the object and the values these have.
*Source code: Stage at which one can read and modify a computer program. Here there are a collection of written commands that compiles to create an executable program.
*Return value: Output of a method. The result type.
*Compiler: Transforms source code into computer language (forces the computer to read the instructions).

## In Chapter 1 we have mentioned the data types int and String. Java has more predefined data types. Find out what they are and what they are used for. To do this, you can check Appendix B, or look it up in another Java book or in an online Java language manual. One such manual is at [http://download.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html](http://download.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html)

## What are the types of the following values?

* 0 int
* "hello" string
* 101 int
* -1 int
* true boolean
* "33" string
* 3.1415 double

## What would you have to do to add a new field, for example one called name, to a circle object? 
You would have to add a new string to the instance
## Write the header for a method named send that has one parameter of type String, and does not return a value.
public void send(String lmao)
## Write the header for a method named average that has two parameters, both of type int, and returns an int value.
public int average(int lol,int kms)
## Look at the book you are reading right now. Is it an object or a class? If it is a class, name some objects. If it is an object, name its class. 
It is a class named textbook. Some objects are contents, part 1, part 2, etc....
## Can an object have several different classes? Discuss. 
Yes and no. An object is under a single class but a class can be inside another class inside another class....
