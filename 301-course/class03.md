# Passing Functions as Props

## lists and keys
keys used to help us identify which keys are changed or which key are added or removed. The best way to pick a key is to use a string that uniquely identifies a list item among its siblings. 


### What does .map() return?

.map() takes an array of values and returns a list of these values.

### How I loop through an array and display each value in JSX ?

Using the mapping then I iterate them using curly braces. In this example I iterated through the loop using map and with li to render them.

```
const numbers = [1, 2, 3, 4, 5];
const listItems = numbers.map((number) =>
  <li>{number}</li>
);
```
### list items 
Each list item needs a unique key. and the key is a special string attribute you need to include when creating lists of elements. 

### What is the purpose of a key?
keys used to help us identify which keys are changed or which key are added or removed. and it is a special string attribute that we include when creating lists of elements.

##  Using the Spread Operator in JavaScript
spread operator is used for three things:

* adding items to arrays.
* combining arrays or objects.
* spreading an array out into a function’s arguments.

### the spread operator

It is referred as an ellipsis three dots (…) and used to expand an iterable object into the list of arguments.

### things spread operator can do.
spread operator can do many things aside the previous things ,such as :

1. Copying an array.
2. Concatenating or combining arrays.
3. Adding an item to a list.
4. Combining objects.

### example of using the spread operator

* combining two arrays: this is calle as array concatenation.

~~~
const myArray = [`🤪`,`🐻`,`🎌`]
const yourArray = [`🙂`,`🤗`,`🤩`]
const ourArray = [...myArray,...yourArray]
console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩
~~~



* Adding a new item to an array: Here we added more fruits to the fruits array.

~~~
const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]
~~~

* Combining two objects into one: This one is useful for combining properties and methods in one object.

~~~
const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂
~~~


## Passing Functions Between Components

### passing functions between components first step
first he made a function inside the parent then passed it to the person object using this. the name of function and used it inside the render.

### increment function
increment function iterates through the names of persons then increment one whenever we click on the choosen name.

### passing method from parent component into a child component?

There are several ways to make sure functions have access to component attributes like this.props and this.state, depending on which syntax and build steps you are using.

### How does the child component invoke a method that was passed to it from a parent component?
It uses this.props or this.state. and then using a button or onclick it will invoke it.

## Things I want to know more about

I want to know how I can pass methods with different examples along with the video example to understand it more.







