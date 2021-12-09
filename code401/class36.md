# Redux - Combined Reducers

## Review, Research, and Discussion

**Why choose Redux instead of the Context API for global state?**

Redux allows you to manage global state, giving you the ability to pass state to any child component. Redux is better for larger application, context API is better for small applications.  

**What is the purpose of a reducer?**

The reducer is a function that takes in action and state and returns the new state of our application.

**What does an action contain?**

An action is an object with type and payload, that tells our reducer what to do and provides it the data it needs to do that action (type, payload).


**Why do we need to copy the state in a reducer?**

We do not want to mutate the original state. Reducers copy state and make changes to that copy.

## Vocabulary Terms

| Term      | Definition |
| ----------- | ----------- |
| immutable state |  state that's value cannot be changed after creation |
| time travel in redux    |  "ability to move back and forth among the previous states of an application" |
| action creator    |  function that creates an action object|
| reducer    |  function that takes in action and state and returns the new state of our application |
| dispatch    |  object with type and payload, that tells the reducer what to do and what to do it with |

[React time travel: the store may not be enough](https://blog.scottlogic.com/2017/03/09/relogic-2.html#:~:text=Time%20travel%20is%20the%20ability,is%20always%20exactly%20the%20same.)

## Preview

**Which 3 things had you heard about previously and now have better clarity on?**

1). Redux

2). Reducer

3). dispatch

**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**

1). Immutable State

2). Redux

3). testing

**What are you most excited about trying to implement or see how it works?**

Redux.  


[Back to Homepage](../README.md)