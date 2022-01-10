# CSS Layout

***

## Controlling the position of elements

CSS has the four *positioning schemes* to allow you to control the layout of a page: normal flow, relative positioning, and absolute positioning.

***

## Creating multi-column layout with floats

Many web pages use multiple columns in their design. This is achieved by using the `<div>` element to represent each column. The following CSS properties are used to position the columns next to each other.

* `width` sets the width of the column
*`float` positions the columns next to each other
* `margin` creates a gap between the columns

***

## Page sizes

Since page sizes and resolution vary, web designers often try to create pages around 960-1000 pixels wide (since most users will be able to see designs this wide on their screen).

***

## Fixed width Layouts

Fixed width layout designs do not change size as the user increases or decreases the size of their browser window. Measurements tend to be given in pixels.

### **Advantages**

* Pixel values are accurate at controlling size and positioning of elements
* The designer has greater control over the appearance and position of items on the page than with liquid layouts
* You can control the lengths of lunes of text regardless of the size of the user's window
The size of the image will always remain the same relative to the rest of the page

### **Disadvantages**

* You can end up with gaps around the edge of a page
* If user has higher screen resolution than the designer's screen, the page can look smaller and text can be harder to read
* If the user increases font sizes, text might not fit into the allotted space
* The design works best on devices that have a site or resolution similar to that of desktop ot laptop computers.
*The page will often take up more vertical space than liquid layout with the same content

***

## Liquid Layout

Liquid layout designs stretch and contract as the user increases/decreases the size of their browser window. These tend to use percentages.

### *Advantages*

* Pages expand to fill the entire browser window
* If the user has a smaller window the page can contract to fit without having to scroll to the side
* Design is tolerant of user setting font sizes larger than the designer intended (since page can stretch)

### *Disadvantages*

* The design can look very different than you intended if you do not have control of the width of the sections
* If the user has a wide window lines of text can become long
* If the user has a narrow window words can be squashed
* If a fixed width item (like an image) is in a box that is too small (because the user made the window smaller) the image can overflow over the text

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
