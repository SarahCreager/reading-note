# Redux - Asynchronous Actions

## Review, Research, and Discussion

**How granular should your reducers be?**

Reducer functions should only depend on the state they are modifying and the actions arguments needed to do so. 

**Pro or Con – multiple reducers can “fire” when a commonly named action is dispatched**

This could be an issue because it could potentially change multiple states between multiple components at once and may alter state we didn't intend to. 

**Name a strategy for preventing the above**


Make sure your reducer action types have unique names that could not be easily mistaken for one another. 

## Vocabulary Terms

| Term      | Definition |
| ----------- | ----------- |
| store |  A collection of the combined reducers that hold state |
| combined reducers    |  an object containing properties of different reducer functions |


## Preview

**Which 3 things had you heard about previously and now have better clarity on?**

1). Redux

2). Reducer

3). testing

**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**

1). combined reducers 

2). Redux

3). Async redux 

**What are you most excited about trying to implement or see how it works?**

Redux.  


[Back to Homepage](../README.md)