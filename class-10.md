# JavaScript Debugging

To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex: some tasks cannot complete until another statement or function has been run.

Each time a script enters a new execution content, there are two phases of activity:

1. Prepare
    * The new scope is created
    * Variables, functions and arguments are created
2. Execute
    * Now it can assign values to variables
    * Reference functions and run their code
    * Execute statements

## Error Types

There are seven built-in types of error objects in JavaScript:

| Object            |Description|
| ---------         | ------------          |
| Error  | Generic error - the other errors are all based upon this error|
| SyntaxError | Syntax has not been followed              |
| ReferenceError       | Tried to reference a variable that is not declared/within scope               |
| TypeError  | An unexpected data type that cannot be coerced            |
| RangeError         | Numbers not in acceptable range     |
| URIError        | encodeURI(), decodeURI(), and similar methods used incorrectly    |
| EvalError         | eval() function used incorrectly   |

## Debugging Workflow

You should try to narrow down the problem area. In a long script this is especially important

1. Look at the error message, it tells you:
    * The relevant script that caused the problem
    * The line number where the problem is
    * The type of error (although the underlying causes may be different)
2. Check how far the script is running. Use tools to write messages to the console to tell how far your script is running
3. Use breakpoints where things are going wrong. They let you pause execution and inspect the values that are stored in variables.

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
