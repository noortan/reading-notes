 ### Chart_js

 Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create. A great way to get started with charts is with Chart.js,

### Drawing a line chart

* To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart. So add this to the body of our HTML page:




* Next, we need to write a script that will retrieve the context of the canvas, so add this to the foot of your body element:

<script> var buyers = document.getElementById('buyers').getContext('2d'); new Chart(buyers).Line(buyerData); </script>

Inside the same script tags we need to create our data, in this instance it’s an object that contains labels for the base of our chart and datasets to describe the values on the chart. Add this immediately above the line that begins ‘var buyers=’:

var buyerData = { labels : ["January","February","March","April","May","June"], datasets : [ { fillColor : "rgba(172,194,132,0.4)", strokeColor : "#ACC26D", pointColor : "#fff", pointStrokeColor : "#9DB86D", data : [203,156,99,251,305,247] } ] }

Drawing a pie chart
Our line chart is complete, so let’s move on to our pie chart. First, we need the canvas element:




Next, we need to get the context and to instantiate the chart:

var countries= document.getElementById("countries").getContext("2d"); new Chart(countries).Pie(pieData, pieOptions);

And finally, we add in the bar chart’s data:

var barData = { labels : ["January","February","March","April","May","June"], datasets : [ { fillColor : "#48A497", strokeColor : "#48A4D1", data : [456,479,324,569,702,600] }, { fillColor : "rgba(73,188,170,0.4)", strokeColor : "rgba(72,174,209,0.4)", data : [364,504,605,400,345,320] }

  ]


}

Chart Types
Line Chart
Bar Chart
Radar Chart
Doughnut and Pie Charts
Polar Area Chart
Bubble Chart
Scatter Chart
Area Chart
Mixed Chart Types  more information
The element




At first sight a looks like the  element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the element has only two attributes, width and height. These are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high.

The element creates a fixed-size drawing surface that exposes one or more rendering contexts, which are used to create and manipulate the content shown. In this tutorial, we focus on the 2D rendering context. Other contexts may provide different types of rendering; for example, WebGL uses a 3D context based on OpenGL ES.

Drawing rectangles

First let's look at the rectangle. There are three functions that draw rectangles on the canvas:

fillRect(x, y, width, height) Draws a filled rectangle.
strokeRect(x, y, width, height) Draws a rectangular outline.
clearRect(x, y, width, height) Clears the specified rectangular area, making it fully transparent. Each of these three functions takes the same parameters. x and y specify the position on the canvas (relative to the origin) of the top-left corner of the rectangle. width and height provide the rectangle's size.
Rectangular shape example

function draw() { var canvas = document.getElementById('canvas'); if (canvas.getContext) { var ctx = canvas.getContext('2d');

ctx.fillRect(25, 25, 100, 100);
ctx.clearRect(45, 45, 60, 60);
ctx.strokeRect(50, 50, 50, 50);


} } more_information

Applying styles and colors

Colors Up until now we have only seen methods of the drawing context. If we want to apply colors to a shape, there are two important properties we can use: fillStyle and strokeStyle.

fillStyle = color Sets the style used when filling shapes.

strokeStyle = color Sets the style for shapes' outlines.

A strokeStyle example

 more_info

Drawing text