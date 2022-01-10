# Images, Color, Text

***

## Images

There are several things to consider when selecting images for your site:

- Include an image in your web pages using HTML
- Pick which image format to use
- Show an image at the right size
- Optimize an image for use on the web to make pages load faster

Images can be used to set the tone for a site. Images should:

- Be relevant
- Convey information
- Convey the right mood
- Be instantly recognizable
- Fit the color palette

Adding Images

- To add an image to a page you need to use the `<img>` element. Know when using the element there is no closing tag
- `src` is imputted intro the tag next. This tells the browser where it can find the image file
- `alt` provides a text description of the image which describes the image if you cannot see it
- `title` can also be used with the `<img>` element to provide additional information about the image. This description is usually dipsplayed when the user hovers over the image.
  - Example: `<img src="images.jpg" alt="This is the description" title="This description shows up when you hover over the image." />`

The `img` attribute also uses two other elements to specify it's size:

- `height` specifies the height of the image in pixels
- `width` speifies the width of the image in pixels
  - Example: `<img src="image.jpg" alt="This is the description" width="600" height="450" />`

Three rules for creating images:

1. Save images in the right format
2. Save images at the right size
3. Measure images in pixels

*There are several tools you can use to edit and save images: `Adobe Photoshop` is the most popular. Other software you can use is `adobe fireworks, pixelmator, paintshop pro, paint.net`*

*Photographs are best saved as JPEGs; illustrations or logos that use flat colors are better saved as GIF.*

***

## Color

Color brings love to your web page.

You can specify colors three different ways:

1. **RGB Values** which express colors in terms of how much red, green, and blue are used to make the color.
    - Example: `rgb(100,100,90)`
2. **Hex Codes** are six-digit that represent the ammount of red green and blue in a color and when written procedes by a has or pound sign.
    - Example: `#ee3e80`
3. **Color Names** are exactly what they sound like: names of colors. There are 147 predefined color names that are recognized by browsers.
    - Example: `DarkCyan`

It is important to ensure that there is enough contrast between any text and the background color (otherwise people will not be able to read your content)

***

## Text

There are two groups of properties that allow you to control the appearance of text:

- The ones the directlt affect the font and appearance ( including the typeface whether bold, italic, or regular as well as the size of the text)
- The ones that would have the same effect on the text no matter what font you were using (including the color of the text and the space between words and lettering)

*Formating of your `text` has a significant effect on how readable your webopage is*

### Typeface Terminology

- `Serif` fonts have extra details on the ends of the main strokes of the lettering. The details are knowns as serifs
  - Example fonts: Georgia, Times, Times New Roman
- `Sans-serif` font have straight end to lettering and therefore are a much cleaner design
  - Exampe fonts: Arial, Verdana, Helvetica
- `Monospace` means every letter in a monospace (or fixed-width) font is the same width. *Non-monospace fonts have different widths*
  - Example fonts: Courier, Courier New
- `Cursive` fonts either have joining strokes or other cursive charateristics such as handwritting styles.
  - Example fonts: Comic Sans MS, Monotype Corsiva
- `Fantasy` fonts are usually decorative fonts and often used for titles. They are not designed for long bodies of text.
  - Example fonts: Impact, Haettenschweiler

- "Weight" - the font weight not only adds emphasis but can also effect the amount of white space and contrast on a page.
- "Style" - `Italic` fonts have a cursive aspect to do some lettering. `Oblique` font styles take the normal style and put it at an angle.
- "Stretch" - In a condensed (or narrow) version of the font, letters are thinner and closer together. In expanded versions they are thicker and further apart.

*When choosing a typeface, it is important to understand that a browser will only display it if it's installed on the user's computer.*

The `font-family` property allows you to specify the typeface that should be used for any text inside the element(s) to which a CSS rule applies. It is possible to specifiy more than one typeface and create an order of prefrence (in case the user does not have your first choice of typeface installed.)This is referred to as a `font stack`.

- For example if you wanted `sans-serif` type, you could write the following: `font-family: Georgia, Times, serif;`

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
