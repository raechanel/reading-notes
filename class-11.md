# Images

You can control the size of your images by using the width and height properties.

Rather than align the img element using the align attribute, use the `float` property to align the images. There are two ways to do this:

1. The float property is added to the class that was created to represent the size of the image (such as the small class in our example.)
2. New classes are created with names such as align-left or align-right to align the image to the left or the right of the page. These class names are used in addition to classes that indicate the size of the image.

Example:

* `img.align-left {`
  
  `float: left;`

  `margin-right: 10px;`
  
  `}`

Centering images using CSS by default they are inline elements. It should be turned into a block-level element using the `display` property with a value of `block`. Once it has been made into a block-level element, there are two common ways in which you can horizontally center an image:

1. On the containing element, you can use the `text-align` property with the value of `center`.
2. On the image itself, you can use the `margin` property and set the values of the left and right margins to auto.

Example:

* `img.align-center {`
  
  `display: block;`

  `margin: Opx auto;`

  `}`

## Background Repeat

The `background-repeat` property can have four values:

| Values     |Description|
| ---------  | ------------          |
| repeat |  the background image is repeated both horizontally and vertically|
| repeat-x | The image is repeated horizontally only              |
| repeat-y | The image is repeated vertically only          |
| no-repeat        | The image is only shown once     |
| fixed     | The background image stays in the same position on the page.   |
| scroll        | The background images moves up and down as the user scrolls up and down the page   |

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
