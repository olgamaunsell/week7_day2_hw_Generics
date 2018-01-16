Generics Homework
Answer the following questions:

1.	What is one benefit of using generics in Java classes?
It allows the class to specify a property that can be instantiated with a  type that is specified when the class is run.


2.	Name an example of a generic class that we have used in Java?
ArrayList

3.	What is the syntax for declaring a generic class?
A generic class can be defined using angle brackets <> with a “letter” representing the generic type

e.g.

This line

class Account {

 would be changed to

class Account<T> {

In all cases in the class where the property which will use the generic type is specified replace the property type with the letter specified in the 1st line.
e.g. private T id;

4.	At what point does the generic type get specified?
When creating a new object of the generic class

5.	Can generic types be of primitive type?

Primitive types can not be passed as type parameters.

e.g. Instead of using primitive type int you would need to use Integer instead.

6.	Can a generic class take more than one type parameters? Yes
