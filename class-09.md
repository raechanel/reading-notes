# Forms and JS Events

***

## Forms

HTML refers to forms as different elements that allow you to collect information from visitors to your site

`FORM CONTROLS`

There are several types of form controls that you can use to collect information from visitors to your site:

* Adding Text:
  * Text input (single line) used for a single line of text such as email addresses and names
  * Password Input is a single line text box but it masks the characters entered
  * Text Area is for longer areas of text, such as messages and comments
* Making Choices:
  * Radio buttons are for use when a user must select one of a number of options
  * Checkboxes used for when a user can select and unselect one or more options
  * Drop-down boxes when a user must pick one of a number of options from a list
* Submitting Forms:
  * Submit buttons used to submit data from your form to another web page
  * Image buttons are used when you are submitting an image
* Uploading Files:
  * File upload allows users to upload files (i.e. images) to a website

Form controls work by a users filling out a form and pressing submit button to submit the information to the server

Each form control is given a name and the text the user types in or the values of the options they select are sent to the server

HTML5 introduces new form elements which make it easier for visitors to fill in forms

***

## Events

***Interactions create events***

Events occur when users click or tap on a link, hover or swipe over an element, type on the keyboard, resize windows, or when the page they requested loads.

***Events trigger code***

When an event occurs, or fires, it can be used to trigger a particular function. Different code can be triggered when users interact with different parts of the page.

***Code responds to users***

The events can trigger the kinds of changes the DOM is capable of. *This is how webpages react to users.*

### Different types of events

* UI Events - Occur when a users interacts with the browser's user interface rather than the web page
  * load
  * unload
  * error
  * resize
  * scroll
* Keyboard events - Occur when a user interacts with the keyboard
  * keydown
  * keyup
  * keypress
* Mouse events - Occur when a user interacts with a mouse, trackpad or touchscreen
  * click
  * doubleclick
  * mouse down
  * mouseup
  * mousemove
  * mouseover
  * mouseout
* Focus events - Occur when an element gains or loses focus
  * focus / focus-in
  * blur / focus-out
* Form events - occur when a users interacts with a form element
  * input
  * change
  * submit
  * reset
  * cut
  * copy
  * paste
  * select

### How Events Trigger JavaScript Code

When the users interacts with the html on the web page, there are three steps involved in getting it to trigger some JavaScript code. These three steps together are known as `event handling`.

1. Select the element node(s) you want the script to respond to [SELECT THE ELEMENT]
2. Indicate which `event` on the selected node(s) will trigger the response [SPECIFY EVENT]
3. States the `code` you want to run when the event occurs [CALL CODE]

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
