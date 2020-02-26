## Forms
### Traditionally, the term 'form' has referredto a printed document that contains spaces for you to fill in information. HTML borrows the concept of a form to refer to different elements that allow you to collect information from visitors to your site.

## Form Structure
### <form>
#### Form controls live inside a <form> element. This element should always carry the action attribute and will usually have a method and id attribute too.
## action
### Every <form> element requires an action attribute. Its value is the URL for the page on the server that will receive the information in the form when it is submitted.
## method
### Forms can be sent using one of two methods: get or post. With the get method, the values from the form are added to the end of the URL specified in the action attribute.

## TEXXT Input
### The <input> element is used to create several different form controls. The value of the type attribute determines what kind of input they will be creating

## Password Input
### type="password" <input> When the type attribute has a value of password it creates a text box that acts just like a single-line text input, except the characters are blocked out. They are hidden in this way so that if someone is looking over the user's shoulder, they cannot see sensitive data such as passwords.

## Check box
### type="checkbox" Checkboxes allow users to select (and unselect) one or more options in answer to a question.
## name
### The name attribute is sent to the server with the value of the option(s) the user selects. When a question provides users with options for answers in the form of checkboxes, the value of the name attribute should be the same for all of the buttons that answer that question.
#### so , many of types we can use it , can apply all of this 

## some ipmortant note 
1. Whenever you want to c XX ollect information from visitors you will need a form which lives inside a
form> element.
2. Information from a form is sent in name/value pairs.
3. Each form control is given a name, and the text the user types in or the values of the options they select
are sent to the server.
4. HTML5 introduces new form elements which make it easier for visitors to fill in forms.

## Lists, Tables and Forms
## as we wotk in last labs , on tabel and list and forms 
### There are several CSS properties that were created to work with specific types of HTML elements, such as lists, tables, and forms.

## important note of this :
1. In addition to the CSS p XX roperties covered in other chapters which work with the contents of all elements, there are several others that are specifically used to control the appearance of lists, tables, and forms.
2. List markers can be given different appearances using the list-style-type and list-style image properties.
3.  Table cells can have different borders and spacing in different browsers, but there are properties you can use to control them and make them more consistent.
4.  Forms are easier to use if the form controls are vertically aligned using CSS.
5.  Forms benefit from styles that make them feel more interactive.

## Event 
## imprtant note : 
1. Events are the browser's way of indicating when something has happened (such as when a page has finished loading or a button has been clicked).
2. Binding is the process of stating which event you are waiting to happen, and which element you are waiting for that event to happen upon.
3. When an event occurs on an element, it can trigger a JavaScript function. When this function then changes the web page in some way, it feels interactive because it has responded to the user.
4. You can use event delegation to monitor for events that happen on all of the children of an element.
5. The most commonly used events are W3C DOM events, although there are others in the HTMLS specification as well as browser-specific events.