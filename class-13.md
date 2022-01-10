# Local Storage

"HTML5 Storage" is refered to as a specification named `Web Storage`. Which t one time, was apart of the HTML5, but was split into it's own specification for uninteresting political reasons.

to check for HTML5 Storage:

`function supports_html5_storage() {
  try {
    return 'localStorage' in window && window['localStorage'] !== null;
  } catch (e) {
    return false;
  }
}`

Insteadof writing this function, you can use `Modernizr` to detect support for HTML5 Storage:

`if (Modernizr.localstorage) {
  // window.localStorage is available!
} else {
  // no native support for HTML5 storage :(
  // maybe try dojox.storage or a third-party solution
}`

HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats.

## STORAGE EVENT OBJECT

|PROPERTY| TYPE | DESCRIPTION |
| --------| -----|------------  |
|key|string|the named key that was added, removed, or modified|
|oldValue|any|the previous value (now overwritten), or null if a new item was added|
|newValue|any|the new value, or null if an item was removed|
|url|string|the page which called a method that triggered this change|

* Note: the url property was originally called uri. Some browsers shipped with that property before the specification changed. For maximum compatibility, you should check whether the url property exists, and if not, check for the uri property instead.

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
