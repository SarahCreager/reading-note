# Context API

## Review, Research, and Discussion

**Describe use cases useState() vs useReducer()**

useState() is used for less complex handling of simple state

useReducer() is preferable to use if you have complex state logic or when the next state depends on the previous

**Why do custom hooks need the use prefix?**

when you put the use prefix before the custom hook, the rules of Hooks apply to it

**What do custom hooks usually do?**

"Custom hooks allow us to have cleaner functional components, remove logic from the UI layer"

[Custom React Hook: When Software Design Meets React Hooks](https://www.wix.engineering/post/custom-react-hook-when-software-design-meets-react-hooks#:~:text=Custom%20hooks%20allow%20us%20to,use%20cases%20to%20reusable%20hooks.)

**Using any list of custom hooks, research and name one that you think will be useful in your applications**

useAuth() to authenticate the user

**Describe how a hook that fetches API data might work**

useEffect() hook that runs when the request for the API updates and invokes a callApi function that fetches data from the API using your API request state

## Vocabulary Terms

| Term      | Definition |
| ----------- | ----------- |
| reducer    |  function that uses the current state and some data to modify it with and ALWAYS returns the new state |


## Preview

**Which 3 things had you heard about previously and now have better clarity on?**

1). reducer

2). useEffect()

3). React hooks

**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**

1). writing tests in React

2). reducer

3). context api

**What are you most excited about trying to implement or see how it works?**

Getting better at React hooks.  


[Back to Homepage](../README.md)