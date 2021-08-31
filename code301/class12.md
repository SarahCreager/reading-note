# CRUD

## Status Codes Based On REST Methods

### In your own words, describe what each group of status code represents:
**100’s** = informational responses.

**200’s** = request was successfully accepted.

**300’s** = redirection code. What is being requested isn't available at the expected location.

**400’s** = client error. The client sent an invalid request to the server.

**500’s** = server errors.

### What is a status code 202? 

This means that the request met all validation needed at the time of sending.

### What is a status code 308?
This means permanent redirect. It tells the client that they need to use a different URL from the one they are currently using.

### What code would you use if an update didn’t return data to a client?

`put`

### What code would you use if a resource used to exist but no longer does?

`patch`

### What is the ‘Forbidden’ status code?

`403` The client doesn't have permission to access the resource.

## Build A REST API With Node.js, Express, & MongoDB - Quick - First 20 minutes

### Why do we need to pull our MongoDB database string out of our server and put it into our .env?

When we deploy our application, we will not want to use our local host, so we create an environment variable. 

### What is middleware?

Code that is run when it gets requested before it is passed to your browser. 

### What does app.use(express.json()) do?

This allows our server to accept json as a body instead of a git element. 

### What does the /:id mean in a route?
 
This allows the route of an ID to be accessed as a parameter.

### What is the difference between PUT and PATCH?

We use PATCH when we only want to update what the user passes us. PUT updates all the information of the user all at once. 

### How do you make a default value in a schema?

`default: enterDefaultValueHere`


### What does a 500 error status code mean?

This means that the server has an error which called the transaction not to work. 

### What is the difference between a status 200 and a status 201?

201 means we successfully created an object. 200 will send by default to say everything was successful, but it isn't as specific. 

[Back to Homepage](../README.md)
