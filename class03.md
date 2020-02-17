# list
## There are lots of occasions when we need to use lists. HTML provides us with
*three different types:*

1. Ordered lists are lists where each item in the list is numbered. For example, the list might be a set of steps for a recipe that must be performed in order, or a legal contract where each point needs to be identified by a section number.(ol)
### order list use number 
2. Unordered lists are lists that begin with a bullet point (rather than characters that indicate order).(ul)
### Unordered lists use bullets
3. Definition lists are made up of a set of terms along with the definitions for each of those terms.(d)
### Definition lists are used to define terminology.

# Boxes
## You can set several properties that affect the appearance of these boxes. In this chapter you will see how to:
1. Control the dimensions of your boxes
2. Create borders around boxes
3. Set margins and padding for boxes
4. Show and hide boxes

## we use width, height
## Limiting Width : min-width, max-width
## ex
~
div.box {
height: 300px;
width: 300px;
background-color: #bbbbaa;}
p {
height: 75%;
width: 75%;
background-color: #0088dd;}
~
# Border, Margin , PADDING
## Border
*Every box has a border (even if it is not visible or is specified to be 0 pixels wide). The border separates the edge of one box from another.*
## Margin
*Margins sit outside the edge of the border. You can set the width of a margin to create a gap between the borders of two adjacent boxes.*
## Padding
*Padding is the space between the border of a box and any content contained within it. Adding padding can increase the readability of its contents.*
## ex
~
p {
width: 275px;
border: 2px solid #0088dd;}
p.example {
padding: 10px;}
~

## border-width and my change color
## EX
~
<p class="one">Hohner's "Clavinet" is essentially an
electric clavichord.</p>
<p class="two">Hohner's "Clavinet" is essentially an
electric clavichord.</p>
<p class="three">Hohner's "Clavinet" is essentially
an electric clavichord.</p>
~

## display 
### inline , block , inline-block

## border-image , radious

# important :
1. You can also control the borders, margin and padding
for each box with CSS.
2. Block-level boxes can be made into inline boxes, and
inline boxes made into block-level boxes.
3. CSS3 has introduced the ability to create image
borders and rounded borders.

## if-else statement 
### as you learn and applied with some roles and condation to do the statement
## form
*if(condition){what you need}else{}*
## switch statement
### maybe like if statement 
## form 
*switch(condtion){case: ... break; case: ... and so to defult: .. break;}*
## we can use true and fales to the condtion , mostly we use it 
## loops 
### for , while , do while
## ex to for loops 
~
var scores= [24. 32, 17]; //Array of scores
var arraylength scores .l ength;// Items in array
var roundNumber = O; //Current round
var msg ''; //Message
var i ; // Counter
//Loop through the items in the array
for (i = O; i < arraylength; i++) {
//Arrays are zero based (so 0 is round 1)
//Add 1 to the current round
roundNumber = (i + l);
// Write the current round to message
msg += 'Round ' + roundNumber + ' : ';
//Get the score from the scores array
msg += scores[i] + '<br / >' ;
document .getElementByid( ' answer') .i nnerHTML msg;
~
## ex for while loop :
~
var i = l ;
var msg = ' ' ;
II Set counter to 1
II Message
II Store 5 times tabl e in a variable
while (i < 10) {
msg += i + ' x 5 = ' + (i * 5) + '<br I>';
i++;
document .getEl ementByid( ' answer') . innerHTML = msg;
~
## ex for do while loop :
~
var i = l;
var msg : I I •
II Set counter to 1
II Message
II Store 5 times table in a variable
do {
msg += i + ' x 5 = ' + (i * 5) + '<br I>' ;s
i++;
} wh il e ( i < 1) ;
II Note how this is already 1 and it still runs
document .getEl ementByl d(' answer').innerHTML = msg;
~



