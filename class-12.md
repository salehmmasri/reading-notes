# Read: 12 - Docs for the HTML <canvas> Element & Chart.js

---

### CHARTS:

- Before we start you should download Chart.js from Here and Here.

- Creating a Chart : All that's required is the script included in your page along with a single <'canvas> node to render the chart.

- the <'canvas> element has only two attributes, width and height. initially be 300 pixels wide and 150 pixels high.

- the <'canvas> element requires the closing tag (<'/canvas>).

- <'canvas> only supports two primitive shapes: rectangles and paths (lists of points connected by lines).

- There are three functions that draw rectangles on the canvas:

    - fillRect(x, y, width, height) Draws a filled rectangle.
    
    - strokeRect(x, y, width, height) Draws a rectangular outline.
    
    - clearRect(x, y, width, height) Clears the specified rectangular area, making it fully transparent.

- Drawing paths :

    - beginPath()_ : Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.
    
    - Path methods : Methods to set different paths for objects.
    
    - closePath() : Adds a straight line to the path, going to the start of the current sub-path.
    
    - stroke() : Draws the shape by stroking its outline.
    
    - fill() : Draws a solid shape by filling the path's content area
- Moving the pen :

    - moveTo(x, y) : Moves the pen to the coordinates specified by x and y.

- Lines : For drawing straight lines

    - lineTo(x, y) : Draws a line from the current drawing position to the position specified by x and y.

- Arcs : To draw arcs or circles

    - arc(x, y, radius, startAngle, endAngle, anticlockwise) : Draws an arc which is centered at (x, y) position with radius r starting at startAngle and ending at endAngle going in the given direction indicated by anticlockwise (defaulting to clockwise).
    
    - rcTo(x1, y1, x2, y2, radius) : Draws an arc with the given control points and radius, connected to the previous point by a straight line.

---

### Colors :

- fillStyle = color : Sets the style used when filling shapes.

- strokeStyle = color : Sets the style for shapes' outlines.
- Transparency

    - globalAlpha = transparencyValue : Applies the specified transparency value to all future shapes drawn on the canvas. The value must be between 0.0 (fully transparent) to 1.0 (fully opaque).This value is 1.0 (fully opaque) by default.
- Line styles :

- lineWidth = value : Sets the width of lines drawn in the future.

- lineCap = type : Sets the appearance of the ends of lines.

- lineJoin = type : Sets the appearance of the "corners" where lines meet.

- miterLimit = value : Establishes a limit on the miter when two lines join at a sharp angle, to let you control how thick the junction becomes.

- getLineDash() : Returns the current line dash pattern array containing an even number of non-negative numbers.

- setLineDash(segments) : Sets the current line dash pattern.

- lineDashOffset = value : Specifies where to start a dash array on a line.



