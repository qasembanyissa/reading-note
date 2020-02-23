## Doming Model
## Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.

### A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams.

## Here's some tips to follow when building your own domain models.
1. When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
2. Model its attributes with a constructor function that defines and initializes properties.
M3. odel its behaviors with small methods that focus on doing one job well.
C4. reate instances using the new keyword followed by a call to a constructor function.
5. Store the newly created object in a variable so you can access its properties and methods from outside.
6. Use the this variable within methods so you can access the object's properties and methods from inside.

## CREATING MANY OBJECTS: CONSTRUCTOR NOTATION
### Sometimes you will want several objects to represent similar things. Object constructors can use a function as a template for creating objects. First, create the template with the object's properties and methods.

## THE BROWSER OBJECT MODEL: THE WINDOW OBJECT
## USING THE BROWSER OBJECT MODEL
## ALL IN THE BODY ARE USED INSEDE WEINDOW
## GLOBAL OBJECTS: STRING OBJECT

## all of this can do changes in code , to build afunction fro specific purpose .
## Ex for amethod and function
~
-(function() {
// PART ONE : CREATE HOTEL OBJECT AND WRITE OUT THE OFFER DETAILS
// Create a hotel obj ect using object l i t eral syntax
var hotel = {
name: 'Park',
roomRate: 240, // Amount in dollars
discount : 15, // Percentage di scount
offerPrice: function() {
var offerRate = this .roomRate * ((100 - this .discount) I 100);
return offerRate;
// Wr ite out the hotel name, standard rate, and the special rate
var hotel Name, roomRate, specialRate; // Declare variables
hotelName = document .getElementByid('hotelName');
roomRate = document.getElementByid('roomRate');
specialRate = document .getElementByld('specialRate');
// Get el ement s
hotelName.textContent = hotel .name; // Write hotel name
roomRate.textContent = '$ ' + hotel . roomRate .toFixed(2) ; // Write room rate
specialRate .textContent = '$' +hotel .offerPrice(); // Write offer pri ce
~
## some ipmortant notes :
* Functions allow you to group a set of related statements together that represent a single task.
*  Functions can take parameters (informatiorJ required to do their job) and may return a value.
* An object is a series of variables and functions that represent something from the world around you.
*  In an object, variables are known as properties of the object; functions are known as methods of the object.
* Web browsers implement objects that represent both the browser window and the document loaded into the browser window.
* JavaScript also has several built-in objects such as String, Number, Math, and Date. Their properties and methods offer functionality that help you write scripts.
* Arrays and objects can be used to create complex data sets (and both can contain the other).

## table 
### There are several types of information that need to be displayed in a grid or table. For example: sports results, stock reports, train timetables.
## all of this method to creat a table
~ 
<table>
The <table> element is used
to create a table. The contents
of the table are written out row
by row.
<tr>
You indicate the start of each
row using the opening <tr> tag.
(The tr stands for table row.)
It is followed by one or more
<td> elements (one for each cell
in that row).
At the end of the row you use a
closing </tr> tag.
<td>
Each cell of a table is
represented using a <td>
element. (The td stands for
table data.)
At the end of each cell you use a
closing </td> tag.
Some browsers automatically
draw lines around the table
and/or the individual cells. You
will learn how to control the
borders of tables using CSS on
pages 309-312 and 337-340.
~

## Ex 
~ 
#### <table>
#### <tr>
#### <th></th>
#### <th>ABC</th>
#### <th>BBC</th>
#### <th>CNN</th>
#### </tr>
#### <tr>
#### <th>6pm - 7pm</th>
#### <td rowspan="2">Movie</td>
#### <td>Comedy</td>
#### <td>News</td>
#### </tr>
#### <tr>
#### <th>7pm - 8pm</th>
#### <td>Sport</td>
#### <td>Current Affairs</td>
#### </tr>
#### </table>
~