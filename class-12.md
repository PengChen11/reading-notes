## [Back to Homepage](https://pengchen11.github.io/reading-notes/readme.md)

# 1. What is HTML Canvas?
The HTML ```<canvas>``` element is used to draw graphics, on the fly, via JavaScript.

The ```<canvas> ```element is only a container for graphics. You must use JavaScript to actually draw the graphics.

Canvas has several methods for drawing paths, boxes, circles, text, and adding images.

# 2. Canvas Examples
A canvas is a rectangular area on an HTML page. By default, a canvas has no border and no content.  

The markup looks like this:
```
<canvas id="myCanvas" width="200" height="100"></canvas>
```

## Draw a Line
```
var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");
ctx.moveTo(0, 0);
ctx.lineTo(200, 100);
ctx.stroke();
```

## Draw a Circle
```
var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");
ctx.beginPath();
ctx.arc(95, 50, 40, 0, 2 * Math.PI);
ctx.stroke();
```

## Draw a Text

```
var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");
ctx.font = "30px Arial";
ctx.fillText("Hello World", 10, 50);
```

