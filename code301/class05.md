# Putting it all together

## React Docs - thinking in React

### How would you break a mock into a component hierarchy?

1). Draw boxes around each component and subcomponent and give them meaningful names.

2). Separate the UI into components. Each component should match a piece of your data model. 

3). Arrange the components in a hierarchy. 

### What is the single responsibility principle and how does it apply to components?
This principal states that each component ideally has one task. If it has multiple responsibilities, it should be broken down into smaller components. 

### What does it mean to build a static version of your application?
A static application does not change based on the user's action. In other words, it has no interactivity. Static applications do not use state.

### Once you have a static application, what do you need to add?
The next step is to add the minimal amount of state that is required for your app to work.

### What are the three questions you can ask to determine if something is state?
*This information below was copied from [React Docs](https://reactjs.org/docs/thinking-in-react.html)*

1). Is it passed in from a parent via props? If so, it probably isn’t state.

2). Does it remain unchanged over time? If so, it probably isn’t state.

3). Can you compute it based on any other state or props in your component? If so, it isn’t state.

### How can you identify where state needs to live?
*This information below was copied from [React Docs](https://reactjs.org/docs/thinking-in-react.html)*

* Identify every component that renders something based on that state.

* Find a common owner component (a single component above all the components that need the state in the hierarchy).

* Either the common owner or another component higher up in the hierarchy should own the state.

* If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.


[Back to Homepage](../README.md)
