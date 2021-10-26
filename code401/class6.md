# Authentication

## Review, Research, and Discussion

**Explain what a “Singleton” is (in Computer Science terms)**

A singleton is a "software design pattern that restricts the instantiation of a class to one "single" instance."

**Explain how the Singleton pattern can be used with Node modules, specifically with classes**

When creating a Class, within the constructor function, see if an instance of that class has already been created. If it has, return it, otherwise create a new instance and return that.

**If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?**

When creating middleware you do not want it to be created more than once, even if it is called multiple times. This could be a use for the Singleton pattern.  

## Vocabulary Terms

| Term      | Definition |
| ----------- | ----------- |
| Router Middleware     | a function that runs between the request and response   |
| Dynamic Module Loading   | invoke code dynamically at run-time       |
| Singleton Pattern      | "software design pattern that restricts the instantiation of a class to one "single" instance"     |
| CRUD -> REST Method Matches   | Create (Put and Post) Read (Get) Update (Put and Patch) Delete (Delete)      |
| Mock Testing   | "creating a fake version of an external or internal service that can stand in for the real one"        |


## Preview

**Which 3 things had you heard about previously and now have better clarity on?**

1). Middleware

2). Writing Tests

3). Restful apps

**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**

1). authentication

2). encoding and encrypting

3). authorization

**What are you most excited about trying to implement or see how it works?**

Authentication in our application. 


#### Sources
[Singleton pattern](https://en.wikipedia.org/wiki/Singleton_pattern)

[CircleCI](https://circleci.com/blog/how-to-test-software-part-i-mocking-stubbing-and-contract-testing/#:~:text=What%20is%20mock%20testing%3F,a%20mock%20can%20be%20used.)


[Back to Homepage](../README.md)