# Text
## Heading 
### heading is # and between 1-6 which mean # , ## , ### , ... to ######
### the mean of h1 , i told the h1 spicelist with large text like title
## see this 
~
<h1>This is a Main Heading</h1>
<h2>This is a Level 2 Heading</h2>
<h3>This is a Level 3 Heading</h3>
<h4>This is a Level 4 Heading</h4>
<h5>This is a Level 5 Heading</h5>
<h6>This is a Level 6 Heading</h6>
~

## Paragraphs
### To create a paragraph, surround the words that make up the
### paragraph with an opening <p> tag and closing </p> tag.

## Superscript & Subscript
### <sup></sup>
*The <sup> element is usedto contain characters that should be superscript such as the suffixes of dates or mathematical  concepts like raising a number to a power such as 22.*

## St rong & Emph asis
### <strong> The use of the <strong> element indicates that its
### content has strong importance.
### <em> : The <em> element indicates emphasis that subtly changes
### the meaning of a sentence.

## <abbr>
### If you use an abbreviation or an acronym, then the <abbr>
### element can be used. A title attribute on the opening tag is
### used to specify the full term.

## <cite>
### When you are referencing a piece of work such as a book,
### film or research paper, the <cite> element can be used
### to indicate where the citation is from.

## <address>
### The <address> element has quite a specific use: to contain
### contact details for the author of the page.

## <ins> , <del>
### del : You put a line on the word 
### del : you put line Under the word

# chapter 10 about CSS basic
## we have some charcter and function and rules in CSS , 
## img , P , h1 , h2 , ... , 
*iside any think i can make any changes i need it like : color , bacground , size , ... so the can make any thing inside my pages by different ways inline or internal or external CSS*
#### ex : h3 { font-family: Arial; color: yellow;}
#### another ex for form of CSS code  : body {
##### font-family: arial;
##### background-color: rgb(185,179,175);}
##### h1 { color: rgb(255,255,255);}

### to best work we should use <style>



## some point important about css
1. CSS treats each HTML e XX lement as if it appears inside its own box and uses rules to indicate how that element should look.
2. Rules are made up of selectors
3. Different types of selectors allow you to target your rules at different elements
4. CSS rules usually appear in a separate document, although they may appear within an HTML page

# basic JS
## JS used to add some information , statment , any think need it outside pages to input information , to ask user about info needit , all this do in JS , and now basic 
*small ex*
~
var today= new Date{);
var hourNow = today.getHours{) ;
var greeting;
if (hourNow > 18) {
greeting= 'Good evening';
else if (hourNow > 12) {
greeting= 'Good afternoon';
else if (hourNow > O) {
greeting 'Good morning';
else {
greeting 'Welcome';
document.write(greeting) ;
~
## i can commitcomments by // or /* and close it by */
### WHAT IS A VARIABLE?
#### A script will have to temporarily store the bits of information it needs to do its job. It can store this data in variables.

### type 
* NUMERIC DATA TYPE : 0.75
* STRING DATA TYPE : 'H.1 ' Ivy! 1
* BOOLEAN DATA TYPE : true
## rules for naming variable :  many roles have is , but you can see it on book at page number 69 
## arrays 
*ex: var colors; colors ['white', 'black', ' custom ']; var el document.getElementByld('col ors'); el . textContent = col ors[O];*

## ARITHMETIC OPERATORS :  see table in page 76 is a small and easy 

# switch statments
## A switch statement starts with a variable called the switch value. Each case indicates a possible value for this variable and the code that should run if the variable matches that value

### ex 
~ 
switch (level) {
case 'O ne ':
title= 'Level 1 ' ;
break;
case 'Two':
tit 1 e = ' Level 2 ' ;
break;
case ' Three' :
title = 'Level 3' ;
break ;
default :
title= 'Test';
break;
}
~
* the have different between if else and switch 
### IF ... ELSE
* There is no need to provide an el se option. (You can just use an if statement.)
* With a series of if statements, they are all checked even if a match has been found (so it performs more slowly than switch).
### SWITCH
* You have a default option that is run if none of the cases match.
* If a match is found, that code is run; then the break statement stops the rest of the switch statement running (providing better performance than multiple if statements).
### EX 
~
var msg;
var level = 2;
II Message
11 Level
c04/js/switch-statement .js
/I Determine message based on level
switch (level) {
case 1:
msg = 'Good luck on the first test ' ;
break;
case 2:
msg = 'Second of three - keep going!';
break;
case 3:
msg = ' Final round, almost there!';
break;
default :
msg = 'Good l uck!';
break;
var el = document.getEl ementByld('answer ' );
el .textContent = msg;
~
#### the end ,, its along time to read all :)
