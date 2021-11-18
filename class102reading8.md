# JavaScript Expressions, Operators and Loops

***

* **Expressions** are any valid set of *literals*, *variables*, *operators*, and expressions that evaluates to a single value.
* **Operations** are used to preform specific mathmetical and logical computations.
* **Loops** offer a quick nd easy way to do something repeatly.

***

## Expressions

### Primary Expressions

Use the `this` keyword to refer to the current object. `this` refers to the calling object in a method. Use `this` either with the dot or the bracket notation.

    - this['propertyName']
    - this.propertyName

### Left-hand-side Expressions

Left values are the destination of an assignment.

### Arithmetic Expressions

Arithmetic evaluates to a number, for example 3.14159. (Generally uses arithmetic operators.)

### String Expressions

String evaluates to a character string, for example, "Fred" or "234". (Generally uses string operators.)

### Logical Expressions

evaluates to true or false. (Often involves logical operators.)

***

## JavaScript Operators

JavaScript has the following types of operators:

* Assignment operators
* Comparison operators
* Arithmetic operators
* Bitwise operators
* Logical operators
* String operators
* Conditional (ternary) operator
* Comma operator
* Unary operators
* Relational operators


### JavaScript Arithmetic Operators

Arithmetic operators are used to perform arithmetic on numbers:

* `+` means addition
* `-` means subtraction
* `*` means multiplication
* `**` means exponentiation
* `/` means division
* `%` means modulus (division remainder)
* `++` means increment
* `--` means decrement

***

## JavaScript Assignment Operators

Assignment operators assign values to JavaScript variables.

Examples:

* The **assignment** operator (=) assigns a value to a variable:
    * let x = 10
* The **addition** operator (+) adds numbers: 
    * let x = 5  
    * let y = 2 
    * let z = x + y

* The multiplication operator (*) multiplies numbers. 
    * let x = 5
    * let y = 2
    * let z = x * y

***

## JavaScript Comparison Operators

* `==` means equal to
* `===` means equal value and equal type
* `!=` means not equal
* `!==` means not equal value or not equal type
* `>` means greater than
* `<` means less than
* `>=` means greater than or equal to
* `<=` means less than or equal to
* `?` means ternary operator

### Grouping Operator
The grouping operator `( )` controls the precedence of evaluation in expressions. For example, you can override multiplication and division first, then addition and subtraction to evaluate addition first.

# Loops

The statements for loops provided in JavaScript are:

* `for` statement - A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.
* `do...while` statement repeats until a specified condition evaluates to false.
* `while` statement executes its statements as long as a specified condition evaluates to true
* `labeled` statement provides a statement with an identifier that lets you refer to it elsewhere in your program
* `break` statement to terminate a loop, switch, or in conjunction with a labeled statement.
    * When you use break without a label, it terminates the innermost enclosing while, do-while, for, or switch immediately and transfers control to the following statement.
    * When you use break with a label, it terminates the specified labeled statement.
* `continue` statement can be used to restart a while, do-while, for, or label statement.
    * When you use continue without a label, it terminates the current iteration of the innermost enclosing while, do-while, or for statement and continues execution of the loop with the next iteration. In contrast to the break statement, continue does not terminate the execution of the loop entirely. In a while loop, it jumps back to the condition. In a for loop, it jumps to the increment-expression.
    * When you use continue with a label, it applies to the looping statement identified with that label.
* `for...in` statement iterates a specified variable over all the enumerable properties of an object. For each distinct property, JavaScript executes the specified statements.
* `for...of` statement creates a loop Iterating over iterable objects (including Array, Map, Set, arguments object and so on), invoking a custom iteration hook with statements to be executed for the value of each distinct property.

***

## Navigation
- [Home](README.md)