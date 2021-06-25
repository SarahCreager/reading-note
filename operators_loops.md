# JavaScript Operators
*(See previous notes on JavaScript Functions and Operators for an introduction to Operators.)*

A JavaScript operator is a symbol that performs an operation. This can include assigning or comparing values, performing arithmetic operations, and more.

```
PRO TIP: A great place to test operators is the webpage console. To get here, right click on the web page and select inspect. Then click the console tab.
```

## Commonly Used Operators

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


### Examples:

**Example 1:**
```
42 == 43 || true
```

reads:
```
true
```

**Example 2:** 
```
42 == 42 || true || true || false
```

reads:
```
true
```

**Example 3:** 
```
42 == 43 && false
```

reads:
```
false
```

**Example 4:** 
```
42 === ‘42’
```

reads:
```
false
```

**Example 5:** 
```
((42 == 42) && true) || false 
```

reads:
```
true
```

**Example 6:** 
```
((true && (false = false)) && (42 == `42`))
```

reads:
```
invalid. 
```

This is because the `=` is an assignment operator. If we switched `=` with `==` this would read true.

# JavaScript Loops

A JavaScript Loop allows you to repeat your code until it returns the expected value. 

For example, if a user enters their password incorrectly, you will need a loop to allow them to re-enter their password (maybe with a prompt telling them they entered it incorrectly). There are many kinds of loops, but in this reading we focused on `while` loops and `for` loops. 

## while loop
A while loop is good to use when you don't know how many times it will take a user to input the correct response. The password example above is an example of a situation where you would use a `while loop`. We don't know how long it will take the user to get it right. 

### Constructing a while loop

**1). You need to establish the base case for the expression before you can enter the loop.**

 *The user will have to enter their password before we can begin the loop to test.*

**2). Now we test the expression**

  *Did the user enter their password incorrectly? If this is `true` that, yes, they did enter it incorrectly, we enter the body of the loop.* 
  
**3). Change the condition of what is being tested.**

  *This step is critical or the loop will repeat over and over endlessly. This is bad.*
  
**4). The user is sent back to the beginning with a prompt telling them they entered the password incorrectly. Enter password again.**

  *The user enters password correctly. Yay!*
  
**6). We take the `false` route and move on from the loop, continuing on in the code.**

  *The user entered their password correct, so it is `false` that the user entered password incorrectly. The loop ends and the user continues on.*

### 2 Key Points about while loops

1). You must set the testing variable before you enter the loop. 

2). You need to make sure that you change the condition of the variable that you are testing inside the loop or it will repeat forever. 

example:
```
userAge =17;
while (userAge <18){
userAge = prompt(`please enter your age again!`)
}
```

## for loop

A for loop is good to use when you know how many times you need to execute the loop. The loop ends when you reach this number.


### Example:
```
for (let i = 2; i < 10; i++) {
	console.log(i);
}
```

### A for loop contains 3 expressions:

1). the start `i = 2`

2). the end `i < 10`

3). how many times you'll increment `i++`

*the example above will read:*

```
2
3
4
5
6
7
8
9
```

The loop stops once `i = 10` because it would finally read `false` since `i` is no longer `< 10`

Adjusting the starting value of `i` can control how long the loop runs for. If `i = 6` in the example above, the loop would only run 4 times. 

[Back to Homepage](README.md)
