# JavaScript Functions
## Control Flow
Control Flow is the order a computer reads and executes functions. This is typically run from the first line of code to the last. However, JavaScript has many structures that can change the order of execution (conditionals, loops, and functions).

## Functions
A JavaScript function is code that executes a task by taking input and returning an output. A function consists of the `function` keyword, a `name` for the function, `()` for the parameters, and `{}` where the code to be executed goes.

```
function getUsername() {

}

```

When Javascript reads a function, it will not execute that function unless you tell it to do so. 



### Invoking a Function
When something invokes (or calls) the function it will execute the code within the {} curly brackets. 

Functions can be invoked from:

* code within JavaScript
* an event like clicking a button on the website
* automatically 

### Function Return
A `return` statement tells the function to stop executing and it returns a value from the function.

# JavaScript Operators
A JavaScript Operator *operates* on data to produce a result. It can assign values, compare values, perform operations, and more. 


**Assignment**

`=` assigns a value to the variable

```
let x = 27;
```

**Adding**

`+` adds numbers or strings together

```
let x = 27;
let y = 3;
let z = x + y;
```

*this will return:*
```
30
```

**Multiplying**

`*` multiplies numbers together

```
let x = 27;
let y = 3;
let z = x * y;
```
*this will return:*
```
81
```
**Addition Assignment**

`+=` adds a value to a variable or string

```
let text1 = "I love";
text1 += "coding!";
```
*text1 will read:*
```
I love coding!
```

Adding numbers together will give you a sum, but if you add a number and a string, a string will be returned. 

```
let x = 20 + 7;
let y = "20" + 7;
let z = "Hey" + 7;
```

*this will return:*

```
27
207
Hey7
```


[Back to Homepage](README.md)