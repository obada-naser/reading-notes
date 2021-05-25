# HTML Links, JS Functions, and Intro to CSS Layout

## Links
Links are a way to allow the user to get from one page to another page inside the same website or from one website to another. And it is a feature that can add it using HTML. The user only needs to click on a specific button on the screen.

### How to create a link in html:-

```
       <a href="url">link text</a>
```
Example :
```
       <p><a href="https://www.w3schoolscom/  ">Visit W3Schools.com!</a></p>

      
```

### Types of using a link:-

**1.Linking to other sites:** and that is done using URL called **absolute URL**. 

**2.Linking to other pages on the same site**:
and that is done using a **relative URL**.Also, it is usually used inside a ` <nav>`

### Other useful codes to use in links:-

* Email Links: It is not that different than any usual links but it only used to open an email. By making inside of the code mailto.
* opening into a new window:we use target to tell the user that this link open into a new window.
* Linking to a specific part in our page: we use id of the element in our code to link it to this part of the page.

## Layout
As we know In CSS, every element is treated as it is own box. however, after increase of developing CSS it allow us now to change the box into either an inline element or block-level element. 

### Block-level elements VS Inline-Level elements:-
* **Block-level elements:** it is a box that act as the main box
* **Inline-Level elements:** it is a box where this surround a text.

![block vs inline](https://media.gcflearnfree.org/content/5e82363212da9215e057b928_03_30_2020/block_vs_inline_diagram.png)

### positioning the elements:-
There many different ways to control the position of your elements and here five types of them: 

1. Normal Flow
2. Relative positioning
3. Absolute positioning
4. fixed Positioning 
5. floating elements

And we can also always use floating property to make it easier.

## Functions

the function is a block of code that is executed when it is provoked by a certain code or active like a user clicking a button.

### Declaring a Function:-
declaring a function needs three things:
function keyword, name of function, and the statement inside the function.

### Calling a Function:-
we call a function by using the name of the function with braces.And inside them we add the information.

### Types of function:

1. Function Declaration:

EX:

 ```

         function area(width, height) return width * height; }; var size= area(3, 4); 
  ```        

2. Function Expression:

EX:

```
var area =  function(width, height) { return width * height; } ; var size=  area(3, 4); 

```

### Variables Scope:-

There are different scopes for variables and that appear in the memory location. first, one local variable and its scope are inside a specific function and the second is a global variable and it is scope is bigger like the whole script.

## Reasons for Pair Programming

pair programming is the most efficient way to program because of these advantages:

* Greater efficiency
* Engaged collaboration
* Learning from fellow students
* Social skills
* Job interview readiness
* Work environment readiness



