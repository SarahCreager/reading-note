# Context API - Behaviors

## Review, Research, and Discussion

**When you have multiple contexts, what component type should you use (class/function) and why?**

My preference would be to use functional components because it handles state more cleanly. 

**What are some good use cases for using the Context API for global state?**

Creating a consistent global layout. Creating a dark mode or light mode. Authentication/authorization

**How can you best test context?**

Test if the child component is consuming it correctly and it is in the shape you expect it to be. 

## Vocabulary Terms

| Term      | Definition |
| ----------- | ----------- |
| context    |  "Context provides a way to pass data through the component tree without having to pass props down manually at every level." |
| useContext()    |  hook that allows you to pass global data to many components without props |
| static context    |  initialize context |

[React Docs](https://reactjs.org/docs/context.html)

## Preview

**Which 3 things had you heard about previously and now have better clarity on?**

1). context

2). useEffect()

3). React hooks

**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**

1). writing tests in React

2). context behaviors

3). reducer

**What are you most excited about trying to implement or see how it works?**

I'd love to implement a dark/light theme.  


[Back to Homepage](../README.md)