# State and Props



## Component Lifecycle Events

We can define components as class or functions using React. THe methods we use is called lifecycle events and it allow you to update UI and application states.


![Lifecycle](https://miro.medium.com/max/2000/0*0saPKFiTUk6W3FYp)

### ‘render’ or the ‘componentDidMount’?

Based off the diagram, It shows that the render happens before the componentDidMount.

### first thing to happen in the lifecycle of React?

The first thing to happen in React Lifecycle is Constructor.

### The order of the the lifecycle of React:
 
 1. constructor
 2. render
 3. componentDidMount
 4. React Updates
 5. componentWillUnmount

 ### What does componentDidMount do?

 It is used as a good place to set up any subscriptions and invoked immediately after a component is mounted. If you do that, don’t forget to unsubscribe in componentWillUnmount().

 ```
 componentDidMount() {
console.log(‘got videos’);
this.getVideos(‘cats’);
}
getVideos(query) {
var options = {
key: this.props.YOUTUBE_API_KEY,
query: query
};
```

## React State Vs Props


### types of things can you pass in the prop
props you pass into the component and must be update outside the component.
state is handel inside that component and you can update it inside the component.

### difference between props and state?

State is internal and controlled by the component itself while props are external and controlled by whatever renders.

### When do we re-render our application?

Whenever there is a change in their state or props. A simple update of the state, from anywhere in the code, causes all the User Interface (UI) elements to be re-rendered automatically.

### Examples of things that we could store in state?
we can store title and sub title .



## Things I want to know more about
I want to understand more about state and props and how to use them properly in our code.