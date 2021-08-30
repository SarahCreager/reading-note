# In memory storage

## Understanding the JavaScript Call Stack

### What is a ‘call’?
A call is when you invoke a function. 

### How many ‘calls’ can happen at once?
Functions are executed, from top to bottom, one at a time. This is synchronous.

### What does LIFO mean?
*This information was quoted from [FreeCodeCamp.com](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4/)*

"Last In, First Out (LIFO): the last function that gets pushed into the stack is the first to pop out, when the function returns."

### Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

[Click here to view image](./assets/callStack.png)

### What causes a Stack Overflow?
*This information was quoted from [FreeCodeCamp.com](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4/)*

"A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accommodate before throwing a stack error."

## JavaScript error messages
*The example code below was provided from [CodeBurst](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)*

### What is a ‘refrence error’?
This error occurs when you try to use a variable that has not been declared. 

```
console.log(name) // Uncaught ReferenceError: name is not defined
```

### What is a ‘syntax error’?
This error occurs when you have a flaw in the syntax. 

### What is a ‘range error’?
This error occurs if you try to manipulate an object with an invalid length. 

```
var name= []
name.length = name.length -1 // Uncaught RangeError: Invalid array length
```

### What is a ‘type error’?
Type errors occur when the data type (number, string, etc) is incompatible. For example, trying to access a property from an undefined variable.

```
var name = {}
name.last // undefined
name.last.first // Uncaught TypeError: Cannot read property 'first' of undefined
```

### What is a breakpoint?
A breakpoint is when you intentionally stop/pause your code to debug.

### What does the word ‘debugger’ do in your code?
Debugger creates a breakpoint in your code. 

[Back to Homepage](../README.md)
