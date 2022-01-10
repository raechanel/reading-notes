# HTML Lists, Control Flow with JS, and the CSS Box Model

***

## Lists

HTML has three different types of lists:

1. ***Ordered Lists*** are list where each item in the list are numbered.
2. ***Unordered Lists*** are list that begin with a bullet point (that don't indicate order)
3. ***Definition Lists*** are used to define terminology

***Ordered Lists*** are created with the `<ol>` element.

***Unordered Lists*** are created with the `<ul>` element.

Each item in the lists (***list item***) is made with the element `<li>`

***

## Control Flow wtih JavaScript

| Data Type | Purpose                                                  |
| --------- | ------------                                             |
| `string`  | Text                                                     |
| `number`  | Number                                                   |
| `Boolean` | true or false                                            |
| `null`     | Empty value                                             |
| `undefined` | Variable has been declared but not yet assigned a value|

### Arrays

***Array*** is a collection of elements otherwise knowns as a list of elements.
An array can have strings, numbers, booleans, other arrays, objects.

`Example: letmixedArr = [1, 'hello', true, [2,3]]`

Arrays have indexes

`let students = ['Rae', 'Kae', 'Shay']`

Rae is index 0 Kay is 1 Shay is 3

To pull Kay: `console.log(students[1])`

Arrays have a length. Very useful to know the length
Example: `console.log(students.length)`

Arrays are convient to add things to

Example: `students[4] = Pat`  

It adds Pat to the array

`.push()` is a mthod that adds the element to the END of the array

`If...Else` statement checks a condition. If it resolves to be true the first code block is executed. If the condition resolves to be false the second code box is run instead.

* Example: `if (score >= 50) {congratulate(; )} "congraulate" is what should be executed if the value is true. else { encourage ();} "encourage" is the code to be executed if the value is false`

### For Loop/While Loop

For loop is great for doing something a certain number of times.

Example: `for (let i = 0;) i < students.length; i++) {console.log(Welcome to Class ' + students[i] + '!')`

}
***

## The CSS Box Model

CSS treats HTML elements as if it is in its own box

Every box haas three properties that can be adjusted to control the appearance:

1. ***Border*** seperates the edge of one box from another

2. ***Margin*** sits outside the edge of the border. This creates a gap between the borders of two adjacent boxes

3. ***Padding*** is the space between the border of a box and any content contained within it.

***

### All Readings

* [Home](README.md)
* [Intro to HTML and JavaScript](class-01.md)
* [Basics of HTML, CSS & JS](class-02.md)
* [HTML Lists, Control Flow with JS, and the CSS Box Model](class-03.md)
* [HTML Links, JS Functions, and Intro to CSS Layout](class-04.md)
* [Images, Color, Text](class-05.md)
* [Object Literals and DOM](class-06.md)
* [Tables, Functions, Methods, and Objects](class-07.md)
* [CSS Layout](class-08.md)
* [Forms and JS Events](class-09.md)
* [Debugging](class-10.md)
* [Images](class-11.md)
* [Chart.js](class-12.md)
* [Local Storage](class-13.md)
* [CSS Transforms, Transitions and Animations](class-14a.md)
* [What google learned about teams?](class-14b.md)
