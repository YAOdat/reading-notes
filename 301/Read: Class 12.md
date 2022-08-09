# CRUD

### In your own words, describe what each group of status code represents:

100’s =
It tells the client that the header part of the request has been received and the server will try to comply with a transmission demand of the client. 

200’s =
It tells the client that its request was accepted.

300’s =

It tells the client that the resource they are requesting isn’t available at the expected location anymore.

400’s =

It is all about the invalid requests a client sent to a server.

500’s =

It indicates to problems with overwhelmed servers or unreachable servers behind proxies, but sometimes it can be directly
related to client requests that trigger error exceptions on the server. 

What is a status code 202?

Accepted, this code tells the client that the request was valid, but its processing will finish sometime in the future.

What is a status code 308?

Permanent Redirect - This tells the client to use another URL to access the resource and not use the current URL anymore. 

What code would you use if an update didn’t return data to a client?
204 Code

What code would you use if a resource used to exist but no longer does?
410

What is the ‘Forbidden’ status code?

The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.


_____________________________________




Why do we need to pull our MongoDB database string out of our server and put it into our .env?
To save something there that is not localy hosted and to protect our information.


What is middleware?

Code that runs but before it gets to your routes.


What does app.use(express.json()) do?

Allows the server to accept json as a body inside an http method element.


What does the /:id mean in a route?

It means that it is a parameter that gives access to whatever the user passes in.


What is the difference between PUT and PATCH?
PUT replaces information.
PATCH updates the information that needs updating, not complete replacement.



How do you make a default value in a schema?

What does a 500 error status code mean?

Internal server error. Generic error, indicates that there is a problem with the server.


What is the difference between a status 200 and a status 201?

 200 - request received and is processing.
 
 201 - request received, was successful, and resulted from the created resource..
