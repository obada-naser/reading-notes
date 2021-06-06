# Chart.js, Canvas


## Chart.js

The main purpose of any chart is to display the data in a different way that could let anyone able to read it and understand it more easily that because it is easier to look at and convey data quickly. Using charts in javascript is not that hard, and that's because of Chart.js, a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page. It’s a well-documented plugin that makes using all kinds of bar charts, line charts, pie charts, and more.

**some examples of Chart.js :** To use it we need to download it then start using it like this.

Drawing a line chart:

```
<canvas id="buyers" width="600" height="400"></canvas>
```

Drawing a pie chart:
```
<canvas id="countries" width="600" height="400"></canvas>

```

Drawing a bar chart:
```
<canvas id="income" width="600" height="400"></canvas>

```

## Canvas

Canvas is an element that is used to draw graphics with javascript and we can regard it as a container for our graphics. Canvas has several methods for drawing paths, boxes, circles, text, and adding images therefore it is the perfect tool that can be used in chart.js. canvas>element has only two attributes, width and height.

### Drawing shapes with canvas
Some of the most helpful usage of the canvas is that it can help us to draw different shapes like:
1. The grid
2. Drawing rectangles
3. Drawing paths
4. Drawing a triangle
5. Lines
6. Arcs
7. Cubic Bezier curves


### Applying styles and colors
It is the way we will learn how to add different colors, line styles, gradients, patterns and shadows to your drawings.

* Colors: there are two important properties to Apply colors to a shape we can use: fillStyle and strokeStyle

* Transparency: we can draw semi-transparent shapes using globalAlpha property.
* Line styles: there are different properties which allow us to style lines. for example:lineWidth = value,lineCap = type, lineCap = type and mothr elements.
* Gradients: we can fill and stroke shapes using linear, radial and conic gradients.
* Patterns: createPattern(image, type) one of the methods of using it.

### Drawing text
After learning how to add styles and colors for the shape. Now it is the time to draw it.

### Drawing text
The rendering context provides two methods to render text: 

1. fillText(text, x, y [, maxWidth])
2. strokeText(text, x, y [, maxWidth])

### Styling text
these are properties which let you adjust the way the text gets displayed on the canvas:

1. font = value
2. textAlign = value
3. textBaseline = value