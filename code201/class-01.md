# Introduction to HTML and JavaScript

## HTML
HTML `HyyperText Markup Language` designates the structure of a web page.

### Opening and Closing Tags
Each HTML element contains an opening tag and a closing tag. 

*Example:*
```
opening tag: <h1>
closing tag: </h1>
```

### Attributes
Attributes tell us more about the content within an element. They contain a `name` and a `value`

*Example:*
```
<h1 lang="fr">Titre</h1>

name: lang
value: fr (french)
```

### HTML Layout

`<head>` this is where you put information about the page.

`<title>` this is an element inside the `<head>` tag that appears in the tab or title bar at the top of your browser. 

`<body>` this is what is shown on the main web page that visitors see.

### Adding a comment 
You can add a comment to your HTML code to better distinguish blocks of code. 

```
<!-- --> (adds a comment)
<!-- Introduction -->
```

### ID Attribute
The ID attribute allows you to identify an element distinctly from other elements in your code. This comes in handy when you are styling different elements of your code with CSS. 

```
<h1 id=”firstheading”>Text goes here</h1>
```

### Class Attribute
The class attribute allows you to identify several elements rather than just one.

```
<h1 class="headings">Text goes here</h1>
```

### Block Elements
Block elements appear on different lines of the web page. 

*Examples:*
```
<p>, <h1> through <h6>, <ul>, <ol>
```

### Inline Elements
Inline elements stay on the same line as the neighboring elements. 

*Examples:*
```
<a> <img> <b>
```

### The `<div>` Tag
The `<div>` tag allows you to group block elements together. In other words, it is a generic container for different HTML code.

### The `<span>` Tag
The `<div>` tag allows you to group inline elements.

### HTML5
HTML5 has new tags that better distinguish groups of code rather than using the `<div>` tag 

*Example:*
```
<nav> 
rather than using: <div id=”nav”>
```

One important thing to remember when using HTML5 tags is that older browsers will require additional information to understand how to read these new tags. 

## Designing Websites
Below are 4 questions you should ask before you begin designing a website. 

### **1). Who is visiting the site?**
This is your target audience. Who you're trying to reach. What is their age, job, income, interests, hobbies? Sometimes it helps to invent fictional people and refer back to them while you create your website. 

### **2). Why are people visiting your site?** 
This is the goal of your user. Their motivation. The thing that triggered them to visit the site today. 

### **3). What information do your visitors need?**
This is the information that will allow them to achieve their goal. It's important to prioritize information. If the viewer finds the site relevant, it will build their trust and they will be more open to viewing extra information or other applicable products. If you aren't relevant, they will leave 

### **4). How often will people visit your site?**
As services or information changes, you will need to update your site. This greatly impacts how you originally design your site. 

### Wireframes
Wireframes help you visually layout where key information needs to go on your site. You can revise, organize, and prioritize information before you begin writing the code. This is the blueprint of your site.  

## Introduction to Programming

Computers use data to create models of the world.

**Events:** a user action recognized by the computer. For example: clicking on email subscription form would trigger an event.

### How Browsers Work

1). Browser receives HTML code

2). Browser creates a model of the page from this code

3). Browser visually displays the page on a screen 

## How HTML, CSS, & JavaScript Fit Together

**HTML** provides information regarding structure of the web page.

**CSS** provides information regarding presentation and style of the web page. 

**JavaScript** makes the page interactive and changes the behavior of the web page. 

[Back to Homepage](../README.md)