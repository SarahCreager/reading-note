# APIs

## API Design Best Practices

### What does REST stand for?
REST stands for Representational State Transfer .

### REST APIs are designed around a __resources__.

### What is an identifer of a resource? Give an example.
An identifier, uniquely identifies a resource. For example, an identifier for an order might be a unique URL. 

### What are the most common HTTP verbs?
 GET, POST, PUT, PATCH, and DELETE.

### What should the URIs be based on?
*This information below was quoted from [Microsoft Docs](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)*
"URIs should be based on nouns (the resource) and not verbs (the operations on the resource)."

### Give an example of a good URI.
*This information below was used from [Microsoft Docs](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)*
```
https://adventure-works.com/orders // Good

https://adventure-works.com/create-order // Avoid
```

### What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
A chatty API has more requests and can expose many small resources. They require the client to send multiple requests to get all the data required. 

### What status code does a successful GET request return?
*This information below was quoted from [Microsoft Docs](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)*
"A successful GET method typically returns HTTP status code 200 (OK). If the resource cannot be found, the method should return 404 (Not Found)."

### What status code does an unsuccessful GET request return?
See above.

### What status code does a successful POST request return?

* If it creates a new resource, status code 201 (Created)
* If it does some processing but doesn't  create a new resource, status code 200 
* If it doesn't return anything, status code 204 (No Content) 
* If the request has invalid input, status code 400 (Bad Request).

### What status code does a successful DELETE request return?
*This information below was quoted from [Microsoft Docs](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)*
"If the delete operation is successful, the web server should respond with HTTP status code 204 (No Content)"

[Back to Homepage](../README.md)