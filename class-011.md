# Mongo and Mongoose

## Review Based on [nosql vs sql](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)

Some differences between SQL and NoSQL databases:

| SQL                    |                    NoSQL                    |
| ---------              | ------------                                |
| Have predefined schema |  Have dynamic schema for unstructured data. |
| Vertically scalable: by increasing the horse-power of the hardware   |  Horizontally scalable: increasing the databases servers in the pool of resources to reduce the load |
| Uses SQL ( structured query language ) for defining and manipulating the data, which is very powerful | Queries are focused on collection of documents. Sometimes it is also called as UnQL (Unstructured Query Language). The syntax of using UnQL varies from database to database |
| Not best fit for hierarchical data storage |  Better for the hierarchical data storage as it follows the key-value pair way of storing data similar to JSON data |
| Databases are primarily called as Relational Databases (RDBMS) | Primarily called as non-relational or distributed database |

***

**What kind of data is a good fit for an SQL database?**

Complex query intensive environment

**Give a real world example.**

I'm not sure

**What kind of data is a good fit a NoSQL database?**

Large data sets

**Give a real world example.**

I'm not sure

**Which type of database is best for hierarchical data storage?**

NoSQL databases

**Which type of database is best for scalability?**

SQL databases are `vertically` scalable whereas the NoSQL databases are `horizontally` scalable. SQL databases are scaled by increasing the horse-power of the hardware. NoSQL databases are scaled by increasing the databases servers in the pool of resources to reduce the load.

***

## Review Based on [sql vs nosql](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)

**What does SQL stand for?**

Structured Query Language

**What is a relational database?**

Database that works with certain assumptions or in a certain way and supports SQL

**What type of structure does a relational database work with?**

Table

**What is a ‘schema’?**

Fields in such things like a table

**What is a NoSQL database?**

Otherwise known as MongoDB which is built to store lots and lots of data very efficiently.

**How does it work?**

Documents in Collections in a Database. There is no schema to the database

**What is inside of a Mongo database?**

Lots of data

**Which is more flexible - SQL or MongoDB? and why.**

Having totally different documents in one collection. Not having to have a format.

**What is the disadvantage of a NoSQL database?**

Not being sure that the data adheres to your format (if you have one)

### Bookmarked Readings

* [Mongoose API](https://mongoosejs.com/docs/api.html#Model)
* [React Router](https://v5.reactrouter.com/web/api/BrowserRouter)

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
* [Things I want to know more about](questions.md)
