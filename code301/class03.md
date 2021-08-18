# Passing Functions as Props

## Lists and Keys

### What does .map() return?
The .map() method returns a new array that is the same length as the parent array.

### If I want to loop through an array and display each value in JSX, how do I do that in React?

```javascript
const colorArray = [red, blue, green];
const newColorArray = colorArray.map(color => <h2>{color}</h2>);
```

### Each list item needs a unique __**key**__.

### What is the purpose of a key?
`Keys` are a clear way to identify items so that you know which items have been modified, added, or removed.


## the Spread Operator

### What is the spread operator?
The spread operator `...` takes in an array or object and expands it into a list of arguments.

### List 4 things that the spread operator can do.

*These examples are used from [Coding At Dawn](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)*

1). Copy an array

2). Add items to a list

3). Combine objects

4). Add to state in React


### Give an example of using the spread operator to combine two arrays.
*This example is used from [Coding At Dawn](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)*

```
const myArray = [`🤪`,`🐻`,`🎌`]
const yourArray = [`🙂`,`🤗`,`🤩`]
const ourArray = [...myArray,...yourArray]
console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩
```

### Give an example of using the spread operator to add a new item to an array.
*This example is used from [Coding At Dawn](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)*

```
const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]
```

### Give an example of using the spread operator to combine two objects into one.
*This example is used from [Coding At Dawn](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)*

```
const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂
```


## How to Pass Functions between Components

### In the video, what is the first step that the developer does to pass functions between components?
He creates the function where the state is that he wants to change. The function will be passed like a prop.

### In your own words, what does the increment function do?
The increment function in this example, responds after the button is clicked, updating the state and creating an element saying "updated" appear. Then, it passes the name back up to the increment method at the parent component that will change the state. The app will re-render and show the new count.

In general, an increment function takes in a variable, changes its value, and returns the new value.

### How can you pass a method from a parent component into a child component?
You can pass a method from parent to child by adding `this.functionName` to the parent component. This method will exist on the component object. You can access it using `this.props.functionName` in the child.

### How does the child component invoke a method that was passed to it from a parent component?
`this.props.functionName();`

[Back to Homepage](../README.md)

