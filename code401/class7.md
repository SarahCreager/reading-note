# Bearer Authorization

## Review, Research, and Discussion

**Write the following steps in the correct order:**

Receive access token
Redirect to a third party authentication endpoint
Register your application to get a client_id and client_secret
Make a request to a third-party API endpoint
Ask the client if they want to sign in via a third party
Receive authorization code
Make a request to the access token endpoint


**What can you do with an authorization code?**

**What can you do with an access token?**

**What’s a benefit of using OAuth instead of your own basic authentication?**

  

## Vocabulary Terms

| Term      | Definition |
| ----------- | ----------- |
| Client ID     | "the client application that will be requesting resources from the Resource Server."  |
| Client Secret   | "only known to your application and the authorization server"      |
| Authentication Endpoint      | only allows authorized devices to connect    |
| Access Token Endpoint   | where the apps makes a request for the access token from a user     |
| API Endpoint   | "a point at which an API -- the code that allows two software programs to communicate with each other -- connects with the software program"      |
| Authorization Code   | "The authorization code is a temporary code that the client will exchange for an access token."     |
| Access Token   | "an access token contains the security credentials for a login session and identifies the user, the user's groups, the user's privileges, and, in some cases, a particular application"      |

## Preview

**Which 3 things had you heard about previously and now have better clarity on?**

1). JWT

2). Authorization Headers

3). Authentication

**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**

1). How to write code that properly using JWT

2). How the flow of information works in the JWT process

3). How to create our own authentication system in it's entirety

**What are you most excited about trying to implement or see how it works?**

I'm excited to implement JWT today. We did this briefly in 301, but we rushed through it so quickly, I still don't completely understand the steps involved. 

#### Sources
[Stack Overflow](https://stackoverflow.com/questions/28418360/jwt-json-web-token-audience-aud-versus-client-id-whats-the-difference#:~:text=The%20client_id%20in%20OAuth%20refers,credentials%20that%20may%20be%20required.)

[Auth0 Docs](https://auth0.com/docs/configure/applications)

[Tech Target](https://searchapparchitecture.techtarget.com/definition/API-endpoint)

[Authorization Code Grant](https://www.oauth.com/oauth2-servers/server-side-apps/authorization-code/)

[Wikipedia](https://en.wikipedia.org/wiki/Access_token)

[Back to Homepage](../README.md)