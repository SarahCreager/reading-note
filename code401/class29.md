# Advanced State with Reducers

## Review, Research, and Discussion

**How can we ensure that an effect hook runs only once?**

"If you want to run an effect and clean it up only once (on mount and unmount), you can pass an empty array ( [] ) as a second argument."

```
useEffect(() => {
  console.log(`hello world`);
}, []);
```

[React Docs](https://reactjs.org/docs/hooks-effect.html#:~:text=If%20you%20want%20to%20run,never%20needs%20to%20re%2Drun.)

**Can useState() update more than one state variable at the same time?**

useState() should be used to update one variable at a time. 

**Is useState() synchronous?**

useState() along with setState() are both asynchronous.

## Vocabulary Terms

| Term      | Definition |
| ----------- | ----------- |
| State Hook    |  "A Hook is a special function that lets you “hook into” React features. For example, useState is a Hook that lets you add React state to function components." |
| Component Lifecycle    | The 3 phases of a lifecycle: Mounting, Updating, and Unmounting. |

[React lifecycle](https://www.w3schools.com/react/react_lifecycle.asp)
[React Docs](https://reactjs.org/docs/hooks-state.html)

## Preview

**Which 3 things had you heard about previously and now have better clarity on?**

1). State

2). useEffect()

3). React hooks

**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**

1). writing tests in React

2). Hooks

3). useEffect()

**What are you most excited about trying to implement or see how it works?**

Getting better at writing tests.  


[Back to Homepage](../README.md)