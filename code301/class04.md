# React and Forms

## React Docs - Forms

### What is a Controlled Component?

It is a component that creates a form element and controls it with the state which remains inside this component. 

### Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
We should store the user's response into state as soon as they enter it. This is because the user can receive instant feedback without having to wait and press the submit button.  

### How do we target what the user is entering if we have an event handler on an input field?
You can add a name attribute to the input element as well as an event handler function that will do something based on the results.

## The Conditional (Ternary) Operator Explained

### Why would we use a ternary operator?
It allows you to write shorter code using conditionals that gives you the same result.

### Rewrite the following statement using a ternary statement:

*original*
```
  if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }
```

*ternary operator*
```
  x===y ? console.log(true): console.log(false);
```

[Back to Homepage](../README.md)
