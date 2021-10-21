# Express REST API

**Name 3 real world use cases where you’d want to change the request with custom middleware**

1). print a message

2). adding a timestamp to the req

3).to trigger an error handler

**True or false: The route handler is middleware?**

False.

**In what ways can a middleware function end the process and send data to the browser?**

`response.end();`  
`response.send();`   
`next();`  

**At what point in the request lifecycle can you “inject” middleware?**

After the HTTP request is made, but before the request runs its callback function.

**What can cause express to error with “Request headers sent twice, cannot start a second response”**

Calling next() multiple times. 

## Vocabulary Terms

| Term      | Definition |
| ----------- | ----------- |
| Middleware      | Any program that runs in between 2 other programs   |
| Request Object   | "the entry point for an application to issue a request to the Library"        |
| Response Object      | "It is the object which communicates between the server and the output which is sent to the client"      |
| Application Middleware   | middleware used specifically in your application        |
| Routing Middleware   | bound to instances of express.Router()        |
| Test Driven Development     | process where coding and testing are closely connected      |
| Behavioral Testing  | testing the external behavior of an application       |

Which 3 things had you heard about previously and now have better clarity on?

1). Middleware

2). Sequelize

3). Writing tests

Which 3 things are you hoping to learn more about in the upcoming lecture/demo?

1). Best error handling practices

2). How specific tests should be

3). More practice with SQL


What are you most excited about trying to implement or see how it works?

I'm excited to connect to a real API and see how the data flows through our app. 

#### Sources
[W3C](https://www.w3.org/Library/User/Using/Request.html#:~:text=The%20request%20object%20is%20the,must%20use%20a%20Request%20object.&text=Examples%20of%20requests%20passed%20to,on%20a%20local%20file%20URL.)

[4Guys](https://www.4guysfromrolla.com/webtech/faq/Beginner/faq3.shtml)

[Back to Homepage](../README.md)