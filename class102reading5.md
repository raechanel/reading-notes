# What is CSS?

**CSS** stands for *Cascading Style Sheets*, which is a language for the presenttion, color, layout and font of a webpage.

**CSS** is a rule-based language, which means you define rules specifying groups of styles that should be applied to particular elements or groups on your webpage.

    For an example: If you wanted the main heading to be shown as a large red text youu would do the following:
    - h1 {
          color: red; 
          font size:5em;
    }

## How to add CSS

There are three ways to inserting a style sheet:

- External CSS
- Internal CSS
- Inline CSS

## External CSS

With an external style sheet, you can change the look of an entire website by changing just one file. Each HTML page must include a refrence to the external style sheet file inside the ***< link >*** element, inside the head section.

## Internal CSS

An internal style sheet may be used if one single HTML page has a unique style. The internal style is defined inside the ***< style >*** element, inside the head section

## Inline CSS

An inline style may be used to apply a unique style for a single element. To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.

## Multiple Style Sheets

If some properties have been defined for the same selector (element) in different style sheets, the value from the last read style sheet will be used.

## Put It Together

All the styles in a page will "cascade" into a new "virtual" style sheet by the following rules, where number one has the highest priority:

1. Inline style (inside an HTML element)
2. External and internal style sheets (in the head section)
3. Browser default

## CSS Color

The color property specifies the ***color*** of text

Tip: Use a background color combined with a text color that makes the text easy to read.

### Navigation

[Home](README.md)