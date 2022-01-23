# Chart.js

`charts.js` is a great way to display data. It is better than using tables, visually. They're easier to look at and convey data quickly, but they're not easy to create. To get started and set up follow these steps:

1. Download `Chart.js`
2. Copy the Chart.min.jsout of the unzipped folder and into the directory you’ll be working in. Then create a new html page and import the script:
`<!DOCTYPE html>`

`<html lang="en">`

  `<head>`

  `<meta charset="utf-8" />`

  `<title>Chart.js demo</title>`

  `<script src='Chart.min.js'></script>`

  `</head>`

   `<body>`

  `</body>`

`</html>`

3. Next you need to draw a line chart. To do that we need to create a canvas element in which Chart.js can draw the chart. We should add this to the body of the HTML page: `<canvas id="buyers" width="600" height="400"></canvas>`

We also need to write a script that will retrieve the context of the canvas, so we add this to the foot of the body: `<script>
    var buyers = document.getElementById('buyers').getContext('2d');
    new Chart(buyers).Line(buyerData);
</script>`

***

## Chart Types

There are 9 types of charts:

| Charts            |Description|
| ---------         | ------------          |
| Line Chart  | a way of plotting data points on a line. Often, it is used to show trend data, or the comparison of two data sets |
| Bar Chart | provides a way of showing data values represented as vertical bars. It is sometimes used to show trend data, and the comparison of multiple data sets side by side.             |
| Radar Chart   | A way of showing multiple data points and the variation between them. They are often useful for comparing the points of two or more different data sets.          |
| Doughnut and Pie Charts  |  Are the most commonly used charts. They are divided into segments, the arc of each segment shows the proportional value of each piece of data.      |
| Polar Area Chart  | Are similar to pie charts, but each segment has the same angle - the radius of the segment differs depending on the value. This type of chart is often useful when we want to show a comparison data similar to a pie chart, but also show a scale of values for context.     |
| Bubble Chart     | Used to display three dimensions of data at the same time. The location of the bubble is determined by the first two dimensions and the corresponding horizontal and vertical axes. The third dimension is represented by the size of the individual bubbles.  |
| Scatter Chart   | are based on basic line charts with the x axis changed to a linear axis. To use a scatter chart, data must be passed as objects containing X and Y properties.  |
| Area Chart  | Both line and radar charts support a fill option on the dataset object which can be used to create space between two datasets or a dataset and a boundary, i.e. the scale origin, start, or end  |
| Mixed Chart Types  | With Chart.js, it is possible to create mixed charts that are a combination of two or more different chart types. A common example is a bar chart that also includes a line dataset. When creating a mixed chart, we specify the chart type on each dataset.  |

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
