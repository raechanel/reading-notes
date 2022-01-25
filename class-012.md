# Retrospective

## Review based on [Status Codes Based on REST Methods](https://www.benlinders.com/2013/which-questions-do-you-ask-in-retrospectives/)

In your own words, describe what each group of status code represents:

100’s = Transfer protocol-level information

200’s = Successful Request

300’s = Need more actions to accept request

400’s = Client error

500’s = The server is at fault

***

**What is a status code 202?**

Accepted - Indicates that the request has been received but not completed yet. It is typically used in log running requests and batch processing.

**What is a status code 308?**

Permanent Redirect - Indicates that the resource is now permanently located at another URI, specified by the `Location` header. It is similar to `301 Moved Permanently` with one exception that the same HTTP method will be used that was used in the prior request.

**What code would you use if an update didn’t return data to a client?**

204

**What code would you use if a resource used to exist but no longer does?**

301

**What is the ‘Forbidden’ status code?**

403

## Review Based on [Build A REST API With Node.js, Express & MongoDB - Quick](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)

**Why do we need to pull our MongoDB database string out of our server and put it into our .env?**

To use something that is not the local host

**What is middleware?**

Code that runs when the server gets a request but before it gets passed to your routes

**What does app.use(express.json()) do?**

Lets the server accept json as a body

**What does the /:id mean in a route?**

Means it is a parameter and to get access to it you would type `req.params.id` to give access to whatever is passed in after the first slash

**What is the difference between PUT and PATCH?**

PATCH updates only what the user passes us

PUT updates all information instead of what is passed

**How do you make a default value in a schema?**

add the default value and make it equal to whatever you want the default to be

**What does a 500 error status code mean?**

That there is an error on the server

**What is the difference between a status 200 and a status 201?**

201 means successfully created an object 200 means everything was successful 201 is more specific about what you were successful in and that something was created.

***

### Other Reading Notes

* [Home](README.md)
* [Introduction to React and Components](class-1.md)
* [States and Props](class-2.md)
* [Passing Functions as Props](class-3.md)
* [React and Forms](class-04.md)
* [Putting It All Together](class-5.md)
* [Node.js](class-6.md)
* [Rest](class-7.md)
* [APIs](class-8.md)
* [Functional Programming](class-9.md)
* [In Memory Stage](class-010.md)
* [Mongo and Mongoose](class-011.md)
* [Things I want to know more about](questions.md)
