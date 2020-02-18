# Links
## Links are the defining feature of the web because they allow you to move from one web page to another — enabling the very idea of browsing or surfing.

## Links are created using the <a> element.
## form like this :
*<a href="http://www.imdb.com">IMDB</a>*

## we can link to other pages in same sites , other sites
## see table in page 84
## email link
*<a href = "email">email name</a>*

## Op ening Links in a New Window
*<a href = "email" target="_blank"> name</a>*

# layout
## Building Blocks
### CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.

*Block-level elementsstart on a new lineExamples include:<h1> <p> <ul> <li>*
*Inline elements flow in between surrounding text Examples include: <img> <b> <i>*

## Containing Elements
### If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.

## Controll ing the Position of El ements
### CSS has the following positioning schemes that allow you to control the layout of a page: normal flow, relative positioning, and absolute positioning. You specify the positioning scheme using the position property in CSS. You can also float elements using the float property.
* Normal flow
* Relative Positioning
* Ab solute positioning
## and another think can use it :
1. z-index
2. Floating El ements (float)
3. Clearing Fl oats (clear)
## ex
~ JS code ~
~
body {
width: 750px;
font-family: Arial, Verdana, sans-serif;
color: #665544;}
p {
width: 230px;
float: left;
margin: 5px;
padding: 5px;
background-color: #efefef;}
.clear {
clear: left;}
~
~ HTML code ~
~
<p class="clear">In 1865, the velocipede (meaning
"fast foot") attached pedals to the front wheel,
but its wooden structure made it extremely
uncomfortable.</p>
~

## important about JS 
### FUNCTIONS & METHODS 
### OBJECTS 
### BUILT-IN OBJECTS
## WHAT IS A FUNCTION?
### Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of st atements).

## declaring function
### to creat a function ,you give it name , and write the statement need it to achieve its task inside the curly braces .

## calling afunction 
### after declaring function , you can them execute all of the statement between its curly braces with one just line of code 

## VARIABLE SCOPE
### The location where you declare a variable will affect where it can be used within your code. If you declare it within a function, it can only be used within that function. This is known as the variable's scope.
* LOCAL VARIABLES
* GLOBAL VARIABLES
