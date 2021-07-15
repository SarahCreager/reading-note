# HTML Links, CSS Layout, JS Functions

## Writing Links

You can link to websites using the following format:
```
<a href="place url here">This is the text the user clicks</a>
```
You can link to other pages in your site using the following format:
```
<a href="README.md">This is the text the user clicks</a>
```

You can open a window with an email address using the following format:
```
<a href="mailto:sarah.f.jamieson@gmail.com">This is the text the user clicks</a>
```

You can open links in a new window using the following format:
```
<a href="place url here" target="_blank">This is the text the user clicks</a>
```

## Layout
CSS organizes HTML elements into boxes. Some elements are block-level and some are inline. 

When designing in CSS, be mindful of the different screen sizes users will be viewing your content on. `Fiixed layouts` do not change size with the size of the browser window. `Liquid layouts` stretch and shrink with the browser window.

`<div>` elements are often used to help group items together for stylizing in CSS. 

## Functions

A JavaScript function combines a series of statements, allowing you to perform a specific task by taking input and returning an output. You can reuse a function rather than rewriting new code for the same task. 

A function consists of the `function` keyword, a `name` for the function, `()` for the parameters, and `{}` where the code to be executed goes.

```
function getUsername() {
     code goes here
}

```

When Javascript reads a function, it **will not** execute that function unless you tell it to do so. 


### Calling a Function
When you invoke or call the function it will execute the code within the {} curly brackets. 

```
getUsername();
```

### Parameters
Sometimes you may need parameters to declare your function. For example:
```
function getSpace(width, height) {
  return width * height;
}
```


### Function Return
A `return` statement tells the function to stop executing and  return a value from the function.

## Pair Programming
Involves putting 2 minds and perspectives together to write code. There is typically a driver and a navigator. The navigator verbally directs the driver while the driver types the code. Pair programming covers all four learning skills to help information better stick.

**Benefits of pair programming:**

1). easier to catch mistakes

2). problem solve together

3). learning from a different perspective

4). improves communication skills

5). helps with preparation for interviews

6). will encounter this in your job

[Back to Homepage](README.md)