# Express

# Review, Research, and Discussion
**What’s the difference between PUT and PATCH?**

`PUT` updates the entire resource all at once because it is a complete representation of a resource. 

`PATCH` allows us to only partially update or edit an existing resource. For example, one field can be updated without modifying the others. 

**Provide links to 3 services or tools that allow you to “mock” an API for development like json-server**

* MockServer
* ReadyAPI
* WireMock

**Compare and contrast Swagger and APIDoc.js 1 Which HTTP status codes should be sent with each type of (un)successful API call?**

Both are API tools that allow you to write documentation data in a separate file like .js or .json.

`Swagger` is more popular than APIDoc.js. "It is a free cloud-based API testing and documentation tool to simplify the validation of any API and generate its corresponding OpenAPI documentation."

`APIDoc.js` "It creates documentation from API annotations in your source code. It includes a default template which uses handlebars, Bootstrap, RequireJS and jQuery for the output of the generated apidata.js and apiproject.js as a html-page;"

*the above was quoted from [Stack Share](https://stackshare.io/stackups/apidocjs-vs-swagger-inspector)*

`401 Unauthorized` you aren't authenticated. The API doesn’t know who you are.

`403 Forbidden` you are authenticated, but you don’t have permission to make the request from that URL. 

`400 Bad Request` you did something wrong in your request. It is a generic error that could mean many things like your request data might have the an incorrect format.

`429 Too Many Requests` you have used all the API request permitted for you plan limit. 

**Compare and contrast SOAP and REST**

`SOAP` has similarities to `REST` in regards to the HTTP protocol and both rely on established rules for exchanging information. 

`SOAP` has more rigid guidelines and relies exclusively on XML which can be extremely complex. It has built in error handling with information that is helpful in fixing the problem. It works with static and strongly defined data formats. In JS a lot of code must be written to perform simple tasks that adhere to the required XML structure. 

`REST` does not require processing and is more flexible. It is an architectural style protocol. It works with looser data formats, allowing you to obtain what you need in a form that's easy to parse with the language of your application. Instead of XML, it relies on a simple URL. 

## Vocabulary Terms

| Term      | Definition |
| ----------- | ----------- |
| Web Server      | refers to hardware and/or software that use HTTP and other protocols to respond to client requests.   |
| Express   | a popular Node web framework        |
| Routing      | the process by which requests (which are specified by URL and HTTP method) are routed to code that takes care of them       |
| WRRC   | web request-response cycle        |

## Reflection

**Which 3 things had you heard about previously and now have better clarity on?**
1). Test Driven Development

2). Creating route handlers in Node

3). NPM

**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**

1). How to successfully write clear and effective tests

2). Working in Node to connect with APIs and reformat the data received (We covered this in 301, but I want more practice with it)

3). Creating and using custom middleware

**What are you most excited about trying to implement or see how it works?**
I am excited about becoming more proficient in testing and learning how to better implement it into my workflow. 

#### Sources:

[MDN Web Docs](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction)

[WhatIs](https://whatis.techtarget.com/definition/Web-server)

[MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/PATCH)

[GeeksforGeeks](https://www.geeksforgeeks.org/difference-between-put-and-patch-request/)

[Smart Bear](https://smartbear.com/blog/soap-vs-rest-whats-the-difference/)

[10 Error Codes When Building APIS](https://www.moesif.com/blog/technical/monitoring/10-Error-Status-Codes-When-Building-APIs-For-The-First-Time-And-How-To-Fix-Them/)

#### Back to Home
[Back to Homepage](../README.md)