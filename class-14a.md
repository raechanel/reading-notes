# CSS Transforms, Transitions and Animations

***

## CSS Transforms

The transform property comes in two different settings, two-dimensional and three-dimensional. Each come with their own properties and values.

The value for the transform property type is followed by a specific amount inside parentheses.

Example:

`div {`

`-webkit-transform: scale(1.5);`
  
`}`

Elements may be distorted, or transformed, on both a two-dimensional plane or a three-dimensional plane. Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes. Three-dimensional transforms work on both the x and y axes, as well as the z axis.

### 2D

The transform property accepts a handful of different values. The rotate value provides the ability to rotate an element from 0 to 360 degrees. Using a positive value will rotate an element clockwise, and using a negative value will rotate the element counterclockwise. The default point of rotation is the center of the element, 50% 50%, both horizontally and vertically:

`.box-1 {transform: rotate(20deg);}`

Using the scale value within the transform property allows you to change the appeared size of an element. The default scale value is 1, therefore any value between .99 and .01 makes an element appear smaller while any value greater than or equal to 1.01 makes an element appear larger.:

`.box-1 {transform: scale(.75);}`

The translate value works a bit like that of relative positioning, pushing and pulling an element in different directions without interrupting the normal flow of the document

It is possible to scale only the height or width of an element using the scaleX and scaleY values. The scaleX value will scale the width of an element while the scaleY value will scale the height of an element. To scale both the height and width of an element but at different sizes, the x and y axis values may be set simultaneously. To do so, use the scale transform declaring the x axis value first, followed by a comma, and then the y axis value.:

`.box-1 {transform: scaleX(.5);}`

The last transform value in the group, skew, is used to distort elements on the horizontal axis, vertical axis, or both. The syntax is very similar to that of the scale and translate values. Using the skewX value distorts an element on the horizontal axis while the skewY value distorts an element on the vertical axis. To distort an element on both axes the skew value is used, declaring the x axis value first, followed by a comma, and then the y axis value.%p

`.box-1 {transform: skewX(5deg);}`

### 3D

With three-dimensional transforms we can rotate an element around any axes. To do so, we use three new transform values, including `rotateX`, `rotateY`, and `rotateZ`.

`.box-1 transform: perspective(200px)rotateX(45deg);}`

The transform is taking place on the z axis, not the x or y axes. When working with three-dimensional transforms, being able to move an element on the z axis does have great benefits, like when building the cube

`.box-1 {transform: perspective(200px) translateZ(-50px);}`

`Skew` is the one two-dimensional transform that `cannot` be transformed on a three-dimensional scale.

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
