# APIs

***

## Review Based on [API Design Best Practices](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)

**What does `REST` stand for?**

Representational State Transfer

**REST APIs are designed around a ____.**

Resource

**What is an identifier of a resource? Give an example.**

a URI that uniquely identifies that resource. For example, the URI for a particular customer order might be: <https://adventure-works.com/orders/1>

**What are the most common HTTP verbs?**

GET, POST, PATCH, DELETE, PUT

**What should the URIs be based on?**

Nouns (the resource) and not verbs (the operations on the resource).

**Give an example of a good URI.**

<https://adventure-works.com/orders>

**What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?**

APIs that expose a large number of small resources. This is a bad thing

**What status code does a successful `GET` request return?**

HTTP status code 200 (OK)

**What status code does an unsuccessful `GET` request return?**

404 (Not Found)

**What status code does a successful `POST` request return?**

HTTP status code 201 (Created)

**What status code does a successful `DELETE` request return?**

HTTP status code 204 (No Content)

## Bookmarked Readings

* [RegExr](https://regexr.com/)

**How would you match a phone number from your city using RegEx?**

Unsure

* [Regex Tutorial](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)
* [Regex 101](https://regex101.com/)

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
* [Things I want to know more about](questions.md)
