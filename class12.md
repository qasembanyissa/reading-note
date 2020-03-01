## <canvas> element
### At first sight a <canvas> looks like the <img> element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the <canvas> element has only two attributes, width and height. These are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high. The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted.

## The rendering context

### The <canvas> element creates a fixed-size drawing surface that exposes one or more rendering contexts, which are used to create and manipulate the content shown. In this tutorial, we focus on the 2D rendering context. Other contexts may provide different types of rendering; for example, WebGL uses a 3D context based on OpenGL ES.

## EX
~
#### <!DOCTYPE html>
#### <html>
####   <head>
####     <meta charset="utf-8"/>
####     <title>Canvas tutorial</title>
####     <script type="text/javascript">
####      function draw() {
####         var canvas = document.getElementById('tutorial');
####         if (canvas.getContext) {
####           var ctx = canvas.getContext('2d');
####         }
####       }
####     </script>
####     <style type="text/css">
####       canvas { border: 1px solid black; }
####     </style>
####   </head>
####   <body onload="draw();">
####     <canvas id="tutorial" width="150" height="150"></canvas>
####   </body>
#### </html>
#### ~

###  The script includes a function called draw(), which is executed once the page finishes loading; this is done by listening for the load event on the document. This function, or one like it, could also be called using window.setTimeout(), window.setInterval(), or any other event handler, as long as the page has been loaded first.

## Drawing shapes with canvas

### The grid

### Before we can start drawing, we need to talk about the canvas grid or coordinate space. Our HTML skeleton from the previous page had a canvas element 150 pixels wide and 150 pixels high. To the right, you see this canvas with the default grid overlayed. Normally 1 unit in the grid corresponds to 1 pixel on the canvas. The origin of this grid is positioned in the top left corner at coordinate (0,0). All elements are placed relative to this origin. So the position of the top left corner of the blue square becomes x pixels from the left and y pixels from the top, at coordinate (x,y). Later in this tutorial we'll see how we can translate the origin to a different position, rotate the grid and even scale it, but for now we'll stick to the default.

## Drawing paths
### Now let's look at paths. A path is a list of points, connected by segments of lines that can be of different shapes, curved or not, of different width and of different color. A path, or even a subpath, can be closed. To make shapes using paths, we take some extra steps:

1. First, you create the path.
2. Then you use drawing commands to draw into the path.
3. Once the path has been created, you can stroke or fill the path to render it.

## Colors
### Up until now we have only seen methods of the drawing context. If we want to apply colors to a shape, there are two important properties we can use: fillStyle and strokeStyle.

### fillStyle = color
## Transparency

### In addition to drawing opaque shapes to the canvas, we can also draw semi-transparent (or translucent) shapes. This is done by either setting the globalAlpha property or by assigning a semi-transparent color to the stroke and/or fill style.

## Drawing text

### The canvas rendering context provides two methods to render text:

### fillText(text, x, y [, maxWidth])
### Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
### strokeText(text, x, y [, maxWidth])
### Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.

## Styling text
### In the examples above we are already making use of the font property to make the text a bit larger than the default size. There are some more properties which let you adjust the way the text gets displayed on the canvas:

#### font = value
#### textAlign = value
#### textBaseline = value
#### direction = value
## 