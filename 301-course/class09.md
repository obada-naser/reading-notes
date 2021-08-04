# FUNCTIONAL PROGRAMMING
## Functional Programming Concepts
### What is functional programming?

Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data.

### What is a pure function and how do we know if something is a pure function?

Here is a very strict definition of purity:

### It returns the same result if given the same arguments (it is also referred as deterministic).
It does not cause any observable side effects.
What are the benefits of a pure function?

The code’s definitely easier to test. We don’t need to mock anything. So we can unit test pure functions with different contexts:

Given a parameter A → expect the function to return value B
Given a parameter C → expect the function to return value D
What is immutability?

Unchanging over time or unable to be changed.

### What is Referential transparency?

Referential transparency = Pure functions + Immutable data.

Reference Functional Programming Concepts 

Node JS Tutorial for Beginners #6 - Modules and require()
### What is a module?

It is a part of a code that represent functionality, and the use of it is to be used with other codes. So instead of writing a code in one file, we split them into pieces of modules.

### What does the word ‘require’ do?

Require will import the module, and enable us to use its functionality

### How do we bring another module into the file the we are working in?

Call module const counter = require('\path').

### What do we have to do to make a module available?

Export part of module that we want it to be available to other files.

