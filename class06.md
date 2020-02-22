## about article
## What is the hardest thing about writing code?

### There are many common answers to this question:

1. Learning a new technology
2. Naming things
3. Testing your code
4. Debugging
5. Fixing bugs
6. Making software maintainable

## and another problem and hardest when we writing code
### The idea behind the Protein Tracker application is that it allows a user to set a goal for the amount of protein to consume in a day.  The user can add protein amounts which are added to a total protein count that is tracked for that user

## If understanding the problem domain is the hardest part of programming and you want to make programming easier, you can do one of two things:

1. Make the problem domain easier
2. Get better at understanding the problem domain

## what is objects

### Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names.

## IN AN OBJECT: VARIABLES BECOME KNOWN AS PROPERTIES
## IN AN OBJECT: FUNCTIONS BECOME KNOWN AS METHODS

## Programmers use a lot of name/value pairs:
* HTML uses attribute names and values.
* CSS uses property names and values.

## In JavaScript:
* Variables have a name and you can assign them a
value of a string, number, or Boolean.
* Arrays have a name and a group of values. (Each
item in an array is a name/value pair because it
has an index number and a value.)
* Named functions have a name and value that is a
set of statements to run if the function is called.
* Objects consist of a set of name/value pairs
(but the names are referred to as keys).

## CREATING· OBJECTS USING LITERAL NOTATION
## ex
~ 
var hotel = {
name: 'Quay',
rooms : 40,
booked: 25,
checkAvailability: function() {
return this.rooms - this.booked;
}
} ;
var elName = document .getElementByld('hotelName');
elName.textContent =hotel .name;
var elRooms = document.getElementByid{'rooms');
elRooms .textContent = hotel .checkAvailability();
~
##  we can CREAT MORE OBJECT LITERALS
### Here you can see another object. Again it is called hote 1, but this time the model represents a different hotel. For a moment, imagine that this is a different page of the same travel website

## doucoment object model
### The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.

## BODY OF HTML PAGE
## ex
~
<html>
<body>
<di v id="page">
<hl id="header">List</hl>
<h2>Buy groceries</h2>
<ul>
<li id="one" class="hot"><em>fresh</em> figs</li>
<li id="two" class="hot">pine nuts</l i>
<l i id="three" class="hot">honey</l i>
<l i id="four">balsamic vinegar</l i>
</ ul>
<script src="js/l i st. js "></scri pt>
</ div>
</ body>
</ html>
~

## the have a dom tree , see table on 187
## METHODS THAT RETURN A SINGLE ELEMENT NODE:
1. getElementByld( 'id' )
2. querySel ector( 1css selector ')
3. getEl ement sByClassName( 'class')
4. getEl ementsByTagName( 'tagName')
5. querySelectorAll ( 'css select')

## so we have a tree to use in looping , in tag like select one id or more or one class and so we can use to connect pages togther , we have a lot of information in this lucture , you can see it and do it .
