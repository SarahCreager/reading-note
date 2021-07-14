# HTML Lists, Control Flow with JS, and the CSS Box Model

## HTML Lists
### Ordered Lists
`<ol>` **ordered lists** use numbers to organize
each list item. Each list item has a `<li>` tag.

### Unordered Lists
`<ul>` **unordered lists** use bullets for each list item and are used when items do not need to be in order of importance. Each list item has a `<li>` tag.

### Definition Lists
`<dl>` **definition lists** are used when defining a term.

They contain the following tags:
```
<dt> the defined term 
<dd> the definition 
```

## Boxes
CSS puts each HTML element into its own box. CSS controls the design and dimensions of these boxes. 

### every box has 3 properties
1). *margin* (outside the border)

2). *border* (edge of the box)

3). *padding* (space between border of box and content inside it)

To center a box in CSS you can use `text-align`

example:
```
title {
  text-align: center;
}
```

## Arrays
Arrays use a single variable to store multiple values. They are good to use when you have a lists of values that are related, but you don't know how many values the list will contain. Arrays do not need to contain the same data type.

```
var design
design = ['large', 'small', 'custom'];
```

Array values are read as a numbered list starting at zero

| Index | Value |
| ----------- | ----------- |
| 0 | large |
| 1 | small |
| 2 | custom |

## Switch Statements
Switch statements allow you to compare a value to multiple outcomes and have a default option if none of the options are met. 

## Loops
### `for` loop contains 3 expressions:

1). the start `i = 2`

2). the end `i < 10`

3). how many times you'll increment `i++`


A `for` loop is good to use when you know how many times you need to execute the loop. The loop ends when you reach this number.

### `while` loop
A `while` loop is used when you don't know how many times it will take a user to input the correct response. 

### 2 Key Points about `while` loops

1). You must set the testing variable before you enter the loop. 

2). You need to make sure that you change the condition of the variable that you are testing inside the loop or it will repeat forever. 

[Back to Homepage](README.md)