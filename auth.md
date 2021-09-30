# Reading notes for class 14 of 301

OAuth is an open standard authorization protocol/framework that describes how servers and services can authenticate access to their assets without sharing the initial, single logon credential. 

signing in with apple or google is a good example of what using OAuth would look like.

the steps to authenticate a user would be first, the website connects to a second website for the user using OAuth. then, the second site generates a one-time token and secret that is unique to the user and server. the first site then gives this token and secret to the initiating users client software. the clients software shows the token and secret to their authorization provider, which could be the second site. if the user is not already authenticated, the client will be asked to authenticate. after this, the client has to approve the authorization transaction to the second site. next comes the users approval. once this is completed, the user is given an approved access token. user gives access token to the first site and from there the second site views the token as proof of authentication. 

OpenID is for logging in to a machine by yourself. while with OAuth it is done for you. 

> Authorization vs Authentication

Authorization is set rules that determine who is allowed to certain things. Authentication is the process of confirming someone is who they say they are. 

Authorization Code Flow is the exchange of a code for a token. This is useful for server-side web apps.

OAuth 2.0 provides a version of the Authorization Code Flow which makes use of a Proof Key for Code Exchange (PKCE). This is for mobile and native apps that require additional security. 

OAuth 2.0 provides the Implicit Flow, which is intended for Public Clients, or applications which are unable to securely store secrets

machine-to-machine apps use Client Credentials Flow for scenarios where username + password auth schemes dont seem useful

device apps that are constrained by their inputs authenticate using the Device Authorization Flow, the device asks the user to go to a link on their computer, smartphone, or anything with a web browser and it authorizes the device

apps can use the Resouce Owner Password Flow which requests that users provide credentials, most of the time in an interactive form. it is only used when redirect-based flows cannot be used

