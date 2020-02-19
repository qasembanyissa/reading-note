# Image 
## There are many reasons why you might want to add an image to a web page: you might want to include a logo, photograph, illustration, diagram, or chart.
## Storing Images on Your 
### If you are building a site from scratch, it is good practice to create a folder for all of the images the site uses.
## Adding Images ,  by <img>
### i have src , alt  , title , and i can change the width and height
## we use unit called pixel to controle in the image
## ex
~
<img src="images/quokka.jpg" alt="A family of
quokka" width="600" height="450" />
~

## we can out image inside main , or in side any statement , like inside <p> , or inside <h> , .. 
## the have think called aline 

## Three Rules for Creating Images
### There are three rules to remember when youare creating images for your website which are summarized below. We go into greater detail on each topic over the next nine pages.

## Tools to Edit & Save Images
### There are several tools you can use to edit and save images to ensure that they are the right size, format, and resolution.
## and the have amany Features to modefy in image

# color
## Foreground Color
### color
## ex 
~
h1 {
color: DarkCyan;}
/* hex code */
h2 {
color: #ee3e80;}
/* rgb value */
p {
color: rgb(100,100,90);}
~
## many tyoe : rgb values ,hex codes , color names , HSL
## Contrast 
### When picking foreground and background colors, it is important to ensure that there is enough contrast for the text to be legible.
## Opacity
## ex
~
p.one {
background-color: rgb(0,0,0);
opacity: 0.5;}
p.two {
background-color: rgb(0,0,0);
background-color: rgba(0,0,0,0.5);}
~
## some important point 
1. Color not only brings your s XX ite to life, but also helps
convey the mood and evokes reactions.
2. There are three ways to specify colors in CSS:
RGB values, hex codes, and color names.
3. Color pickers can help you find the color you want.

# Text
## The properties that allow you to control the appearance of text can be split into two groups:
* Those that directly affect t ●● he font and its appearance
(including the typeface, whether it is regular, bold or italic,
and the size of the text)
* Those that would have the same effect on text no matter
what font you were using (including the color of text and
the spacing between words and letters)
## Specifying Typefaces
### font-family
*The font-family property allows you to specify the typeface that should be used for any text inside the element(s) to which a CSS rule applies. The value of this property is the name of the typeface you want to use.*
## font-size
### The font-size property enables you to specify a size for the font. There are several ways to specify the size of a font.

## Type Scales
### You may have noticed that programs such as Word, Photoshop and InDesign offer the same sizes of text.

## Bold
## font-weight
## ex : .credits {font-weight: bold;}
## font-style
## ex : .credits {font-style: italic;}
## Leading : line-height
## ex : p {line-height: 1.4em;}
## and so many style you can use it ,,
## important 
* There are properties to control t XX he choice of font, size, weight, style, and spacing.
* There is a limited choice of fonts that you can assume most people will have installed.
* If you want to use a wider range of typefaces there are several options, but you need to have the right license to use them.
* You can control the space between lines of text, individual letters, and words. Text can also be aligned to the left, right, center, or justified. It can also be indented.
* *You can use pseudo-classes to change the style of an\ element when a user hovers over or clicks on text, or when they have visited a link.