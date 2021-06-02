# Error Handling & Debugging

learning javascript is interesting and getting advance with it is a lot of fun. However, when we get advance with it means more and more errors that make it sometimes harder therefore javascript made it easier to spot those errors and handle them by using tools provided in consoles and javascript. like, order of exection and that is by spotting the source of the error.


## The Stack
The compiler always processes one line of code at a time but when we have a function between these lines of codes it piles the new function on top of what it is doing now and that is called stacking.  


## Execution Context 

Always, there is one global execution context and when we make a new function it creates a new execution context that affects the scope of the newly made variable inside the function.

### Execution Context and Hoisting
whenever the script enters a new execution it does two important avtivities:-

   **1. Preparing :** it means new scope, new function,variables, and arguments are created and also value of the this keyword is determined.

   **2. Executing :** in this part means assigning values to variables, refrencing functions, and then execting statements.

## Errors
when we have an error that means javascript told us about it and it means in javascript language has thrown an exception and starts looking for exception-handling code. 

### Some Error objects
Some of object errors that help us to find our mistakes and browsers have tools for this. And here are some of those 
error:
* Error
* Syntax Error
* ReferenceError
* TypeError
* RangeError
* URI Error
* EvalError

### How to Deal with Errors

1. **Debug the script to fix the errors.**

This is about eliminating the causes of an error by going through the problem and narrowing it down to small pieces. that is done by asking ourselves where is the problem using the console and when we find it, we look at what exactly the error is to try and solve it. special tool used is called the breakpoint tool that used to break the exection of the code and then check the variables.

2. **Handle errors gracefully.**  

this one is used when we know that our code might fail, that is when we should use try, catch, and finally. Try means try this block of code, catch means if an exception happens try this code and if both methods do not work finally will always get executed. Or otherwise try throwing an errors like generating our errors so it does not ruin our execution.









