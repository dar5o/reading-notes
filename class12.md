# Reading for class 12

>chart.js
`var ctx = document.getElementById('canvas').getContext('2d');`

chart.js is a javascript plugin that uses HTML5's canvas element to draw a graph on the page. it makes stylizing a bar chart, line chart, or pie chart incredibly easy. you draw a line chart using the `<canvas>` element. 
There are three functions that draw rectangles on the canvas:

- fillRect(x, y, width, height)
  + Draws a filled rectangle.
- strokeRect(x, y, width, height)
  + Draws a rectangular outline.
- clearRect(x, y, width, height)
  + Clears the specified rectangular area, making it fully transparent.

Each of these three functions takes the same parameters. x and y specify the position on the canvas (relative to the origin) of the top-left corner of the rectangle. width and height provide the rectangle's size. One very useful function, which doesn't actually draw anything but becomes part of the path list described above, is the moveTo() function. You can probably best think of this as lifting a pen or pencil from one spot on a piece of paper and placing it on the next.

- moveTo(x, y)
  + Moves the pen to the coordinates specified by x and y.

If we want to apply colors to a shape, there are two important properties we can use: fillStyle and strokeStyle.

- fillStyle = color
  + Sets the style used when filling shapes.
- strokeStyle = color
  + Sets the style for shapes' outlines.

color is a string representing a CSS `<color>`, a gradient object, or a pattern object.

The canvas rendering context provides two methods to render text:

- fillText(text, x, y [, maxWidth])
  + Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
- strokeText(text, x, y [, maxWidth])
  + Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.