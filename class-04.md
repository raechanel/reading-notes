# HTML Links, JS Functions, and Intro to CSS Layout

***

## HTML Links

Links allow you to move from one web page to another - enabling the idea of browsing or surfing.

There are different kinds of links:

- Links from one website to another

- Links from one page to another on the same website

- Links from one part of the webpage to another part of the same webpage

- Links that open in a new browser window

- Links that  open your email program to address a new email to someone

Links are created using the `<a>` element. Users can click on anything between the opening and closing `<a>` tag. You specify which page you want to link to using the `href` attribute.

- Example: `<a href="http://www.imbd.com">IMDB</a>`

  - The opening link tag is `<a href="http://www.imbd.com">`

  - This is the page the link takes you to: `http://www.imbd.com`

  - This is the text the user clinks on: `IMBD`
  
  - This is the closing tag: `<a>`

Email links: `<a href="mailto:jon@example.org">Email Jon</a>`

Opening links in a new window: `<a href="http://www.imbd.com" target="_blank">Internet Movie Database</a>`

Linking to a specific part on the same page: `<a href="#top">` would link to the h1 element at the "top" whose id attribute has a value of top.

***

## CSS Layout

CSS treats HTML as if it is in it's own box. The box will either be **block-level** or an **inline** box.

- **Block-level** elements start on a new line
  - Examples: `<h1> <p> <ul> <li>`
- **Inline** elements flows inbetween the surronding text
  - Examples: `<img> <b> <i>`
- If one block-level element sits inside another block-level element then the outer box is known as the **containing** or **parent** element.
  - Examples: `<div>`

### CSS Positions

There are 4 types: **Fixed**, **Static**, **Relative**, **Absolute**

## JS Functions

**Functions** let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can resuse the function (rather than repeating the same set of statements).

When you ask it to perform its task, its known as **calling** the function.

Pieces of information passed to a function are known as **parameters**.

When you write a function and expect an answer, the response is known as a **return value**

To create a function, you give it a name and the write the statements needed to achieve its task inside the curly braces. This is knowns as a **function declaration**.

You decalre a function using the *function* keyword.

You should give the function a *name* or *identifier* followed by parenthesis.

The *statements* that perform the task sit in a code block. (Inside the curly braces)

- Example: `function sayHello() {
  document.write('Hello');
}`

- In this example:
  - `function` is the function keyword
  - `sayHello()` is the function name
  - {document.write('Hello');}` is the code block inside the curly braces

To call a function you code your function name: `sayHello();`

***

### All Readings

- [Home](README.md)
- [Intro to HTML and JavaScript](class-01.md)
- [Basics of HTML, CSS & JS](class-02.md)
- [HTML Lists, Control Flow with JS, and the CSS Box Model](class-03.md)
- [HTML Links, JS Functions, and Intro to CSS Layout](class-04.md)
- [Images, Color, Text](class-05.md)
- [Object Literals and DOM](class-06.md)
- [Tables, Functions, Methods, and Objects](class-07.md)
- [CSS Layout](class-08.md)
- [Forms and JS Events](class-09.md)
- [Debugging](class-10.md)
- [Images](class-11.md)
- [Chart.js](class-12.md)
- [Local Storage](class-13.md)
- [CSS Transforms, Transitions and Animations](class-14a.md)
- [What google learned about teams?](class-14b.md)
