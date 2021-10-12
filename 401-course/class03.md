# Maps, primitives, File I/O

## Primitives vs. Objects
Java has a two-fold type system consisting of primitives such as int, boolean and reference types such as Integer, Boolean. Every primitive type corresponds to a reference type.

Here we discuss the cons and pros of both.

### Single Item Memory Footprint

 primitive type variables:

* boolean – 1 bit
* byte – 8 bits
* short, char – 16 bits
* int, float – 32 bits
* long, double – 64 bits

reference type :

* Boolean – 128 bits
* Byte – 128 bits
* Short, Character – 128 bits
* Integer, Float – 128 bits
* Long, Double – 192 bits

### Memory Footprint for Arrays
We can see the difference in the image below:

![ primitive type variables:](https://www.baeldung.com/wp-content/uploads/2018/08/plot-memory-bits.gif)

###  Performance

the primitive types live in the stack while the reference types live in the heap. This is a dominant factor that determines how fast the objects get be accessed.


### Default Values

primitive type variables:

Default values of the primitive types are 0 for numeric types, false for the boolean type, \u0000 for the char type. For the wrapper classes, the default value is null.


reference type :
while the reference types might acquire a value (null) that in some sense doesn't belong to their domains.


## Exceptions 

In Java “an event that occurs during the execution of a program that disrupts the normal flow of instructions” is called an exception. This is generally an unexpected or unwanted event which can occur either at compile-time or run-time in application code

### Types of Exception in Java with Examples

1. ArithmeticException. It is thrown when an exceptional condition has occurred in an arithmetic operation.
2. ArrayIndexOutOfBoundsException.
3. ClassNotFoundException.
4. FileNotFoundException. 
5. IOException. 
6. InterruptedException. 
7. NoSuchFieldException. 
8. NoSuchMethodException.



## Scanner Objects

1. Breaking Input into Tokens.
2. Treats all input tokens as simple String values.
3. Supports tokens for all of the Java language's primitive types (except for char), as well as BigInteger and BigDecimal.
4. We have to mention the locale, because thousands separators and decimal symbols are locale specific.


## What I learned 

I learned that there are difference between the primitive and reference data types. also there something called exceptions that interrupts the work of the execution.
