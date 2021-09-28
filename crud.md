> crud 

### rest status codes

- 100s
  + info
- 200s
  + accepted request
- 300s
  + redirects the client, expected info is not available at the loc they requested from
- 400s
  + client side error
- 500s
  + server side error

status code 202 means a requestes was accepted but hasnt processed asynchonously, it may not be complete yet

status code 308 means the resource you requested with be available at a new URL, a permanent redirect

404 not found is what you return if the client didnt recieve any data

410 gone is like a 404 not found code except we know that the resource being requested existed in the past but is currently unavailable

403 forbidden is the forbidden status code, the client doesnt have permissions to access the resource

> rest api

### node, express, and mongodb

- Why do we need to pull our MongoDB database string out of our server and put it into our .env?
  + to test locally and deploy on a live server

middleware is software between client and server

`app.use(express.json())` will let the server accept json as a body instead of post/get

:/id in route is the parameter

put creates an object while patch updates it without erasing data that was stored previously

default: value will make a default value in a schema

500 status code means there was an error on the server

the difference between a status 200 and a status 201 is a successful post request
