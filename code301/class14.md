# Authentication

## What is OAuth

### What is OAuth?

*The information below was quoted from this article [CSO](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html)*

"OAuth is an open-standard framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential."

### Give an example of what using OAuth would look like.

When you login to a website and it gives you the option to login with your Google account. 

### How does OAuth work? What are the steps that it takes to authenticate the user?

*The information below was quoted from this article [CSO](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html)*

"Two unrelated sites or services trying to accomplish something on behalf of users or their software. All three have to work together involving multiple approvals for the completed transaction to get authorized." (see website above for detailed step-by-step process)

### What is OpenID?

OpenId is similar to OAuth, but it is for computers logging into machines verses people. 

## Authorization and Authentication flows

### What is the difference between authorization and authentication?

Authentication verifies the user.
Authorization veriifies what the user can access. 

### What is Authorization Code Flow?

This process exchanges an authorization code with a token.

### What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

This is an additional secuirty step that some apps require. A `Code Verifier` is used to exchange for a token rather than just an authorization code. 

### What is Implicit Flow with Form Post?

It is used if the application only requires an ID token to authenticate the user.


### What is Client Credentials Flow?

This is used when the system authenticates and authorizes the app instead of a user.

### What is Device Authorization Flow?

*The information below was quoted from this article [AuthO Docs](https://auth0.com/docs/authorization/flows)*

"With input-constrained devices that connect to the internet, rather than authenticate the user directly, the device asks the user to go to a link on their computer or smartphone and authorize the device."

### What is Resource Owner Password Flow?

It is not as safe, but highly-trusted applications can use this to request user credentials using an interactive form.

[Back to Homepage](../README.md)