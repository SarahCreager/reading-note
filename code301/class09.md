# Functional Programming

## Functional Programming Concepts

### What is functional programming?
*This information was quoted from [Wikipedia](https://en.wikipedia.org/wiki/Functional_programming)*

"Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data"

### What is a pure function and how do we know if something is a pure function?
*This information was referenced from [Medium.com](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)*

A function is pure if:

* It returns the same result when given the same arguments

* It does not cause any observable side effects

### What are the benefits of a pure function?
It makes your code easier to test under different contexts.

### What is immutability?
Immutable data cannot change its state after being created.

### What is Referential transparency?
*This information was quoted from [Medium.com](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)*

"if a function consistently yields the same result for the same input, it is referentially transparent."

## Node JS Tutorial for Beginners #6 - Modules and require()

### What is a module?
A module is a JavaScript file that communicates with an external application based on their functionality.

### What does the word ‘require’ do?
It imports the module into another file. 

### How do we bring another module into the file the we are working in?
```
require('./filename);
```

### What do we have to do to make a module available?
We have to explicitly say we want it available to other files.

```
module.exports=name;
```

[Back to Homepage](../README.md)