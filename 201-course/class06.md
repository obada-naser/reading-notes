# Problem Domain, Objects, and the DOM

## Object Literals

The object is something who has **properties** and **methods** like in real-world there are many objects for example car is an object and every car has it is own properties and methods. But in general every car has the same properties such as weight and color and methods such as how to start and stop functions and that same thing is applied in JavaScript.

### Creating An object in JavaScript:
Object in JavaScript, variables become known as the properties of this object and functions is the methods of the object. For example, if we created an object of the hotel we can make properties for this hotel like the number of rooms or the name of this hotel as for the methods, like how this hotel checks room availability and any other methods who describe how this hotel works.


example of how to create and object and how to access this object:
```
var person = {
  firstName: "John",
  lastName : "Doe",
  id       : 5566,
  fullName : function() {
    return this.firstName + " " + this.lastName;
  }
};

objectName.methodName();
name = person.fullName();


```

## Document Object Model




DOM or document object model describes two things one of how browsers create a model of an HTML page and how JavaScript can access and update the contents of a web page. when the browser loads a web page it creates a model of DOM tree, and it is stored in the browser's memory. This tree consists of four main types of nodes and these are :

* Documents node
* Elements node 
* Attributes nodes
* Text nodes

### Accessing the DOM tree

There are multiple and different ways on how to access any element in the DOM tree using dom queries and it may return one element or multiple elements and that called NodeList.

1. Return an individual element node:-

This one uses methods that returns a single element node and uses these methods:

* >getElementByld('id')

* >querySelector( 'css selector')

2. Return one or more element nodes:-

This one is a method that returns one or more element nodes or as called a NodeList. Nodelist is a collection of element nodes. The methods are: 

* >getElementsByClassName('class')
* >getElementsByTagName('tagName')
* >querySelectorAll ('css selector')

We can repeat an action for an entire NodeList using looping. Also, traverse through the DOM using different methods.

### Updating/Getting the DOM tree

when we finally access the element or a group of elements, Now we use methods to get/update these selected elements and these elements are :

1. **Access or update a text nodes:**
We can change and retrieve text using different methods like nodeValue, textContent with innerText. 

2. **Working with HTML contents:**
There are different ways to add or remove content from a DOM tree: 
    * one using the **innnerHTML** property.
    * the other is by using DOM manipulation

3. **Access or update attributes values:** 
when we already entered the DOM node we can now also change the attributes of this element by only two steps:
    *  first by selecting the element node with the attribute we need to change follow it with a period symbol.
    *  Then use one of those methods to work with it:  getAttribute(), hasAttribute(), setAttribute(), removeAttribute().
    
