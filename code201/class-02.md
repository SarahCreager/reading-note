# Basics of HTML, CSS, and JavaScript

## Common HTML Tags Used for Text

| Syntax      | Description |
| ----------- | ----------- |
| `<h1>`      | heading       |
| `<p>`   | paragraph        |
| `<b>`      | bold       |
| `<i>`      | italic       |
| `<sup>`      | raises to a power or raises letters like the *th* in 4th       |
| `<sub>`      | opposite of `<sup>` lowers letters or numbers as in CO2       |
| `<br` `/>`      | adds a line break in paragraph       |
| `<hr` `/>`      | add a horizontal line between sections       |
| `<strong>`      | adds emphasis to text       |
| `<em>`      | adds subtle emphasis, appears italic       |
| `<blockquote>`      | used for longer quotes       |
| `<q>`      | used for shorter quotes, adds " "       |
| `<abbr>`      | abbreviation       |
| `<cite>`      | references work       |
| `<dfn>`      | used when defining new terminology for the first time      |
| `<address>`      | contains address       |
| `<ins>`      | inserted, underlines text       |
| `<del>`      | deleted, draws a line through text       |
| `<s>`      | no longer relevant, draws a line through text       |

## Introducing CSS
CSS allows you to style your HTML elements by associating rules with each element you choose to style. Each CSS rule contains a `selector` and a `declaration`.

```
selector: h1
```

```
declaration: color:blue
```

**Result:**
```
h1 {color:blue;}
```

Each `declaration` contains a `property` and a `value`. 

```
property: color
```
```
value: blue
```

### External CSS
You can use the `<link>` element within the `<head>` of your html code to tell the browser when to find the external CSS information. The link element does not require a closing tag. 

The `<link>` element should have the following attributes: 

```
href="pathtoCSSfile"
```
```
type="text/css"
```
```
rel="stylesheet"
```

### Internal CSS
You can add CSS internally to your page by using the `<style>` element. This would typically be placed in the `<head>`. 

The `<style>` element should have the following attribute:

```
type="text/css"
```

### CSS Rules
1). If there are two rules applied to the same element, the second will overrule the first. 

2). If one is rule is more specific, it will overrule the more general rule. 

3). If a rule has `!important` after the value it will override any other rules.  

```
p {
  font-size: 50% !important;}
}
```
## Basic JavaScript
**Declaring a variable**
```
var userName;
```

**Assigning value to a variable**
```
userName = Sarah;
```
If you don't assign a value to a variable, it will be *undefined*.

### Rules for naming variables
1).name must begin with letter, $, or _

2). name can contain letters, numbers, $ or _

3). name cannot contain keywords/reserved words

4). name is case sensitive

5). name should describe the information being stored

6). if name contains two words, camel case should be used (userName)
### Data Types
* numeric

* string (letters and characters)

* boolean (true or false)

### JavaScript Operators

A JavaScript operator is a symbol that performs an operation, like assigning or comparing values and performing arithmetic operations.


### Commonly Used Operators

| Assignment Operators | Meaning |
| ----------- | ----------- |
| = | assigns value |
| x += y | reads x = x + y |
| x -= y | reads x = x- y |
| x++ | reads x = x + 1 |



| Comparison Operators | Meaning |
| ----------- | ----------- |
| == | reads `true` if both sides are equal |
| != | reads `true` if both sides are not equal |
| == | reads `true` if both sides are equal |
| === | reads `true` if both sides are equal and the same type |
| !== | reads `true` if both sides are the same type but not equal or are different types |
| > | reads `true` if left side is greater than right |
| >= | reads `true` if left side is greater than or equal to right |



### Logical Operators
---------------------- 
`&&` : reads `true` if both sides are true 

`||` : (means OR) reads `true` if either side is true. Will stop reading at first item if true. Will read `false` if both sides are false 

### If Statement
An if statement evaluates a condition to see if it is true or false. 

**Example:**
```
if (age>= 21) {
  msg = 'You may enter site';
} else {
  msg = 'Please click away';
}
```


[Back to Homepage](../README.md)