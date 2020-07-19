# EASILY CREATE STUNNING ANIMATED CHARTS WITH CHART.JS:

Setting up
The first thing we need to do is download Chart.js. Copy the Chart.min.js out of the unzipped folder and into the directory you’ll be working in. Then create a new html page and import the script:

```<script src='Chart.min.js'></script>```

you can do many charts like :
1. line chart.
2. Pie chart.
3.bar chart

# Chart.js:


**Installation**
You can download the latest version of Chart.js from the GitHub releases or use a Chart.js CDN. Detailed installation instructions can be found on the installation page.

# Basic usage:


At first sight a ```<canvas>``` looks like the ```<img>``` element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the ```<canvas>``` element has only two attributes, width and height. These are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high. The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted.


# Drawing shapes with canvas:


**The grid**
The origin of this grid is positioned in the top left corner at coordinate (0,0). All elements are placed relative to this origin.

**Drawing rectangles:**

fillRect(x, y, width, height)
Draws a filled rectangle.
strokeRect(x, y, width, height)
Draws a rectangular outline.
clearRect(x, y, width, height)


**Drawing paths**
beginPath()
Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.
Path methods
Methods to set different paths for objects.
closePath()
Adds a straight line to the path, going to the start of the current sub-path.
stroke()
Draws the shape by stroking its outline.
fill()
Draws a solid shape by filling the path's content area.

**Bezier and quadratic curves**

quadraticCurveTo(cp1x, cp1y, x, y)
Draws a quadratic Bézier curve from the current pen position to the end point specified by x and y, using the control point specified by cp1x and cp1y.
bezierCurveTo(cp1x, cp1y, cp2x, cp2y, x, y)
Draws a cubic Bézier curve from the current pen position to the end point specified by x and y, using the control points specified by (cp1x, cp1y) and (cp2x, cp2y).


# Applying styles and colors:

**Colors**
fillStyle = color
Sets the style used when filling shapes.
strokeStyle = color
Sets the style for shapes' outlines.


**Transparency**
globalAlpha = transparencyValue


**Gradients**

createLinearGradient(x1, y1, x2, y2)
Creates a linear gradient object with a starting point of (x1, y1) and an end point of (x2, y2).
createRadialGradient(x1, y1, r1, x2, y2, r2)
Creates a radial gradient. The parameters represent two circles, one with its center at (x1, y1) and a radius of r1, and the other with its center at (x2, y2) with a radius of r2.



**Patterns**

createPattern(image, type)



# Drawing text:


Drawing text
The canvas rendering context provides two methods to render text:

fillText(text, x, y [, maxWidth])
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
strokeText(text, x, y [, maxWidth])
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.


**Styling text:**

font = value
The current text style being used when drawing text. This string uses the same syntax as the CSS font property. The default font is 10px sans-serif.
textAlign = value
Text alignment setting. Possible values: start, end, left, right or center. The default value is start.
textBaseline = value
Baseline alignment setting. Possible values: top, hanging, middle, alphabetic, ideographic, bottom. The default value is alphabetic.
direction = value
Directionality. Possible values: ltr, rtl, inherit. The default value is inherit.




