# `<Login />` and `<Auth />`

## Review, Research, and Discussion

**Why is the Context API useful?**

It gives you a way to pass global data to children components without having to manually pass down props through every component. 

**Can a component outside of a provider get its context?**

Yes, it can consume the context using the useContext() hook.

**What are some common use cases for using the Context API?**

You could use context API to create a consistent application global layout. You could use it to create a dark mode or light mode. It can also be useful for authentication/authorization

**Describe “Context Hell”**

`Context Hell` is the messy code you get from nesting multiple `Context.Provider`s and passing them as children of each other. 

## Vocabulary Terms

| Term      | Definition |
| ----------- | ----------- |
| global state    |  data that all components share |
| global context    |  a way to share global state to all components without passing down props |
| provider   |  "allows consuming components to subscribe to context changes." |
| consumer   |  "A React component that subscribes to context changes. " |

[React Docs](https://reactjs.org/docs/context.html#:~:text=Context.Consumer&text=A%20React%20component%20that%20subscribes,and%20returns%20a%20React%20node.)

## Preview

**Which 3 things had you heard about previously and now have better clarity on?**

1). context

2). useEffect()

3). context providers and consumers

**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**

1). writing tests in React

2). Authentication/Authorization

3). context behaviors

**What are you most excited about trying to implement or see how it works?**

I'd love to implement a dark/light theme.  


[Back to Homepage](../README.md)