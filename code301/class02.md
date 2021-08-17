# State and Props

## React Lifecycle

### Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

The *render phase* occurs first in the diagram. 

### What is the very first thing to happen in the lifecycle of React?

Mounting is the first phase in the lifecycle of React. The constructor is the first method used.

### Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

1). constructor
2). render
3). React updates
4). componentDidMount
5). componentWillUnmount

### What does componentDidMount do?

This method is used after a component is rendered to execute the code in React.

## React State Vs Props

### What types of things can you pass in the props?

Props are similar to arguments in a function. Props allow you to pass information from parent to children components. You can pass information that initializes your component or you can pass information that will be rendered to the page.

### What is the big difference between props and state?

If you are handling and updating information inside the component, you want to use state. If you are handling and updating information outside of the component, you want to use props.

### When do we re-render our application?

When the state of an application is changed, the application will re-render.This is why state is used when you need to re-render or update the application based on something the user has done. 

### What are some examples of things that we could store in state?

In the video some examples were:

* A counter: this is something that will need to be updated and re-rendered based on the action is is counting.

* A form: this is something that will be updated by user as information is inputted into the form.


[Back to Homepage](../README.md)
