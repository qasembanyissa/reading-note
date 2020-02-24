## Layout
### Containing Elements
#### If one block-level element sits inside anotherblock-level element then the outer box is known as the containing or parent element.

## Controll ing the Position of El ements
### CSS has the following positioning schemes that allow you to control the layout of a page: normal flow, relative positioning, and absolute positioning. You specify the positioning scheme using the positio property in CSS. You can also float elements using the float property.

## position:static
## ex 
~
### HTML
#### <body>
#### <h1>The Evolution of the Bicycle</h1>
#### <p>In 1817 Baron von Drais invented a walking
#### machine that would help him get around the
#### royal gardens faster...</p>
#### </body>
### CSS
body {
width: 750px;
font-family: Arial, Verdana, sans-serif;
color: #665544;}
h1 {
background-color: #efefef;
padding: 10px;}
p {
width: 450px;}

### position:fixed
#### Fixed positioning is a type of absolute positioning that requires the position property to have a value of fixed. It positions the element in relation to the browser window. Therefore, when a user scrolls down the page, it stays in the exact same place. It is a good idea to try this example in your browser to see the effect. To control where the fixed position box appears in relation to the browser window, the box offset properties are used.

## The have a many method we can use it in layot
## important note
1. div> elements are often used as containing elements
to group together sections of a page.
2. Browsers display pages in normal flow unless you
specify relative, absolute, or fixed positioning.
3. The float property moves content to the left or right
of the page and can be used to create multi-column
layouts. (Floated items require a defined width.)
4. Pages can be fixed width or liquid (stretchy) layouts.
5. Designers keep pages within 960-1000 pixels wide,
and indicate what the site is about within the top 600
pixels (to demonstrate its relevance without scrolling).
6. Grids help create professional and flexible designs.
7. CSS Frameworks provide rules for common tasks.
8. You can include multiple CSS files in one page.