# Component Lifecycle / useEffect() Hook

## Review, Research, and Discussion

**Why do we not need more .html pages in a multi-page React app?**

React remains on one html page and renders components as needed. Each “page” is a rewrite of the DOM.

**If we wanted a component to show up on every page, where would we put it and why?**

Inside the `<BrowserRouter />`, outside a `<Route />`


**What does routing do with the components that were rendered when a new route is requested?**

The previous component is unmounted. 

**What does props.children contain?**

"this.props.children is used to display whatever you include between the opening and closing tags when invoking a component."

[A quick intro to React’s props.children](https://codeburst.io/a-quick-intro-to-reacts-props-children-cb3d2fce4891)

**How do useState() and this.setState() differ?**

useState() updates state in functional components

setState() updates state in class components

## Vocabulary Terms

| Term      | Definition |
| ----------- | ----------- |
| State Hook    |  "A Hook is a special function that lets you “hook into” React features. For example, useState is a Hook that lets you add React state to function components." |
| Mounting and Un-Mounting     | creation and deletion ("setup" and "cleanup") |

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