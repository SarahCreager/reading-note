# Debugging

## Error Messages
Error messages in the console will tell you a description about the error what file the error occurred on and what line. It's good to remember that just because an error occurred on a specific line, doesn't mean that is where the error is. It could have occurred on an earlier line of code, but the error occurred where the code stops running. 

## Debugging Workflow
* breakdown the code into smaller sections to test
* write variables into the console to see their values
* call functions in the console to check if they are working correctly
* check if objects in the console contain the methods and properties they should. 

You can use `console.group();` and `console.groupEnd();` to group together pieces of information in your console. 

## Breakpoints
Breakpoints pause the script on any line you place the breakpoint (debugger). When you run the script, it will stop here. You can hover over variables to see their value. 

## Debugging Tips
* strip back your code (commenting out sections)
* explain the code out loud
* search Google
* review forums

`undefined` is for properties, methods, and values

`null` is for objects 

## Common Errors
* typos
* not declaring variables or functions
* single double quotes don't match
* not having unique ID attributes in HTML
* missed a semicolon. 
* missing brackets or curly braces
* missing a parameter when calling a function
* using = instead of ===

[Back to Homepage](README.md)