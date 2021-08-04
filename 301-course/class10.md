# Javascript Call Stack:
## Understanding the JavaScript Call Stack
### What is a 'call'?
is primarily used for function invocation (call). Since the call stack is single, function(s) execution, is done, one at a time, from top to bottom. It means the call stack is synchronous.

### How many 'calls' can happen at once?
is done, one at a time, from top to bottom. It means the call stack is synchronous.

### What does LIFO mean?
stands for Last In First Out it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.

### What causes a Stack Overflow?
A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

## JavaScript error messages
### What is a 'refrence error'?
This is as simple as when you try to use a variable that is not yet declared you get this type os errors.This is also a common thing when using const and let, they are hoisted like var and function but there is a time between the hoisting and being declared so when you try to access them a reference error occurs, the fact that this happens to let and const is called Temporal Dead Zone (TDZ).

### What is a 'syntax error'?
it's in the name of the errors, but like it says itself, this occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.

### What is a ‘range error’?

Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.

var foo= [] foo.length = foo.length -1 // Uncaught RangeError: Invalid array length

### What is a ‘type error’?

This types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

### What is a breakpoint?

The breakpoint can also be achieved by putting a debugger statement in your code in the line you want to break.

### What does the word ‘debugger’ do in your code?

Debugging is the process of detecting and removing of existing and potential errors (also called as ‘bugs’) in a software code that can cause it to behave unexpectedly or crash. we can achieve from it the breakpoint

## Things I want to know more about?

I want to know more about errors.