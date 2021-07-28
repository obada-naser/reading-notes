# Putting it all together React

## Thinking in React

 ### How would you break a mock into a component heirarchy?

 
 Using the single responsibility principle, which is a technique that each component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.
 Separate UI into components, where each component matches one piece of the data model.
 By Drawing boxes around every component and subcomponent in the mock and give them all names.
 for example:

 ![example](https://reactjs.org/static/eb8bda25806a89ebdc838813bdfa3601/6b2ea/thinking-in-react-components.png)

 ### What is the single responsibility principle and how does it apply to components?
 A computer-programming principle states that every module, class or function in a computer program should have responsibility over a single part of that program’s functionality, and it should encapsulate that part. All of that module, class or function’s services should be narrowly aligned with that responsibility.

 ### What does it mean to build a ‘static’ version of your application?
 Building a version that takes the data model and renders the UI but has no interactivity.

 Once you have a static application, what do you need to add?
 Adding interactivity by identifing the minimal but complete Representation Of UI State

 ### What are the three questions you can ask to determine if something is state?
 1. Is it passed in from a parent via props? If so, it probably isn’t state.
 2. Does it remain unchanged over time? If so, it probably isn’t state.
 3. Can you compute it based on any other state or props in your component? If so, it isn’t state

 ### How can you identify where state needs to live?
 Identify every component that renders something based on that state.
 Find a common owner component (a single component above all the components that need the state in the hierarchy).
 Either the common owner or another component higher up in the hierarchy should own the state.
 If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.
 props are a way of passing data from parent to child. If you’re familiar with the concept of state, don’t use state at all to build this static version. State is reserved only for interactivity, that is, data that changes over time.

## Things I want to know more about

I want to know how javascript works with commands and respond to the important tasks. 

