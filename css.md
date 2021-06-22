# What is CSS?
While HTML builds the foundation of a website, CSS integrates design elements to style it. CSS is a rule based language that specifies how your website will appear to users. 

### Documents
CSS presents documents to users in a stylistic manner. A document is a structured file of text with markup language. HTML is the most commonly used markup language.


### Presenting

This is the action of converting a document to show it to a user. Browsers (or user agents) present documents in a visual way to the user. 


# CSS Syntax
1). First you want to select the element that is to be styled. 

*for example:*

If I want to change the font size of my paragraph I would select `<p>`
```
p

```

2). Then you add a set of curly braces `{}` which will have a declaration inside of them. 

```
p {

}
```

3).These declarations contain a *property* and a *value*. The property (font-size) of the element comes first, followed by an allowable value (5em). 

*for example:* 

``` 
p {
    font-size: 5em;
}
```

# 3 Ways to Insert CSS
## 1). External CSS
Add a `<link>` element inside the head section. 

*for example:*
```
<!DOCTYPE html>

<html>
    <head>
        <link rel=”stylesheet” href=”style.css type=text/css”>
    </head>
</html>
```

This external style sheet can be added via terminal using the touch command and must end with a .css extension. 

## 2). Internal CSS
To apply CSS internally, use the `<style>` element inside the `<head>` section. 

```
<!DOCTYPE html>

<html>
    <head> 
        <style>
         p {
             font-size: 5em;
         }
        </style>
    </head>
    <body>> 
        <main>
            <p> I love coding </p>
        </main>
    </body>
</html>

```

## 3). Inline CSS
Add the `style` attribute to the element you want to style in your HTML code. 

```
<!DOCTYPE html>

<html>
    <body>
        <main>
         <p style="color:blue;"> I love coding.</p>
        </main>
    </body>
</html>
```

[Back to Homepage](README.md)