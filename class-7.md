# REST

## Review based on (How I explained REST to my brother)[]

**Who is Roy Fielding?**

The guy who helped write the first web server, HTTP.

**Why don’t the techniques that we use today work well when we need to be able to talk to all of the machines in the world?**

When Fielding and his colleagues started building the web, being able to talk to any machine anywhere in the world was a primary concern. But most of the techniques developers later used to get computers to talk to each other didn't have those requirements. You just needed to talk to a small group of machines.

**What is the HTTP protocol that Fielding and his friends created?**

The protocol is all about applying verbs to nouns. For instance, when you go to a web page, the browser does an HTTP GET on the URL you typed in and back comes a web page

**What does a GET do?**

"Gets" stuff

**What does a POST do?**

If one system needs to add something to another system

**What does PUT do?**

If a system wants to replace something in another system

**What does PATCH do?**

Partial update

### Other Reading Notes

* [Home](README.md)
* [Introduction to React and Components](class-1.md)
* [States and Props](class-2.md)
* [Passing Functions as Props](class-3.md)
* [React and Forms](class-04.md)
* [Putting It All Together](class-5.md)
* [Things I want to know more about](questions.md)
