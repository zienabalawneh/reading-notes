# Introductory HTML and JavaScript

# Chapter 1- Structure

+ **HTML**hyper text markup language 
+ **HTML** pages are text documents
+ **Html** use tags like opening tags and end tags

1. `<head>` appears at the top of search engines only and does not appear on the page

2. `<body>`In this part, all its contents appear on the page, which can be viewed by the user and may contain several tags of it

The use of headings and subheadings in any document often reflects a hierarchy of information. For example, a document might start with a large heading, followed by an introduction or the most important information


# Chapter 8- Extra markup
### DOCTYPEs

  because there have been several versions of HTML, each web page should begin with a DOCTYPE declaration to tell a browser which version of HTML the page is using the use of a DOCTYPE can also help the browser to render a page correctly.
  
### Comments in HTML

 comments are not visible to users in the main browser window, they can be viewed by anyone who looks at the source code behind the page.

 + Syntax

 `<!-- comment goes here -->`

### ID Attribute

Every HTML element can carry the id attribute. It is used to uniquely identify that element from other elements on the page. Its value should start with a letter or an underscore (not a number or any other character).

It is important that no two elements on the same page have the same value for their id attributes (otherwise the value is no longer unique).

### Class attribute 

Every HTML element can also carry a class attribute. Sometimes, rather than uniquely identifying one element within a document, you will want a way to identify several elements as being different from the other elements on the page.

### Block Elements

Some elements will always appear to start on a new line in the browser window. 
+ Examples of block elements are`<h1> ` ` <p> ` ` <ul> `   `<li> `

### Inline Elements

Some elements will always appear to continue on the same line as their neighbouring elements.
+ Examples of inline elements are  `<a> `  `<b> `  `<em> ` `<img> `


#### Grouping Text & Elements In a Block


1. block-elements.html HTML The `<div>`element allows you to group a set of elements together in one block-level box.


2. The `<span>` element acts like an inline equivalent of the` <div>` element It is used to either:


+ Contain a section of text where there is no other suitable element to differentiate it from its surrounding text


+ Contain a number of inline Elements The most common reason why people use `<span> `elements is so that they can control the appearance of the content of these elements using CSS. You will usually see that a class or id attribute is used with `<span>` elements:

    1. To explain the purpose of this `<span> `element

    2. So that CSS styles can be applied to elements that have specific values for these attributes.

### IFrames

An iframe is like a little window that has been cut into your page — and in that window you can see another page. The term iframe is an abbreviation of inline frame.
 
  + Syntax
   
     `<iframe>`



### Information About Your Pages


+ The  `<meta> ` element lives inside the  `<head> ` element and contains information about that web page.

+ It is not visible to users but fulfills a number of purposes such as telling search engines about your page, who created it, and whether or not it is time sensitive. (If the page is time sensitive, it can be set to expire.)

+ The  `<meta> ` element is an empty element so it does not have a closing tag. It uses attributes to carry the information.

# Chapter 17- html5 layout

+ HTML5 is introducing a new set of elements that help define the structure of a page.
### New html5 layout elements
 HTML5 introduces a new set of elements that allow you to divide up the parts of a page.
 #### Headers & Footers
 + Syntax

     `<header> <footer> ` 
#### Navigation
+ Syntax

    `<nav>` 
#### Sections
+ Syntax

    `<section>`
#### Heading Groups
+ Syntax

    `<hgroup>`

#### Figures
+ Syntax

   `<figure> <figcaption>`

#### Sectioning Elements

+ Syntax

    `<div>`

#### Link
+ Syntax

      `<a>`


# Chapter 18 - Process & Design

**Prpcess you can use when you are creating website:**
It looks at who might be visiting your site and how to ensure the pages feature the information those visitors need.

#### it is important to look at:

+ How to understand the audience your site may attract and what information they will expect to find on it.

+ How to organize information so that visitors can find what they are looking for

+ Design theory for presenting information in a way that helps visitors achieve their goals

+ Design tips to help you create more attractive and professional sites
+ who is the site for:
  1. What is the age range of your ausience ?

  2.  Will your site appeal to more women or man or mix ?

  3. Which country do you visitor live in ?

+ Why people visit your website ?
After you know who your visitors are, you nees to consider why they are coming . Some people will across your website by chance but most will visit for specific reason

+ What information your visitors need

+ How often people will visit your site ?

+ Site maps

   The aim is to create a diagram of the pages that will be used to structure the site. This is known as a site map and it will show how those pages can be grouped.

+ WireFrames

  A wireframe is a simple sketch of the key information that needs to go on each page of a site. It shows the hierarchy of the information and how much space it might require.
![WireFrames](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQi1RdTGWPFoMp7TwyK7TkDBcG3N5RCFRqaSQ&usqp=CAU)

+ Getting your message across using design

  The primary aim of any kind of visual design is to communicate. Organizing and prioritizing information on a page helps users understand its importance and what order to read it in.

+  Visual hierarchy
 refers to the order in which your eyes perceive what they see. It is created by adding visual contrast between the items being displayed. Items with higher contrast are recognized and processed first.


# JS book

#  Programming with JavaScript

A script is a series of instructions that the computer can follow in order to achieve a goal. 
**JavaScript** allows you to make web pages more interactive by modifying the contents, reflecting that modification on the web page, and responding to what the user is doing.
+ JavaScript is used to add or remove elements, attributes, and text to the page, for example:
     + Change the size or position of the `<img>` element

**Html elements are added to the content of a page to discribe its structure**

+ We are using Javascript when a certain event occurs. For example, it can be triggered when:
 1. A button is pressed
 2. The link is clicked (or clicked) on
 3. The information is added to a form

### EXAMPLES OF JAVASCRIPT IN THE BROWSER 

 1. Access the content of the page 
 2. Modify the content of the page 
 3. Program rules or instructions the browser can follow 
 4. React to events triggered by the user or browser 

### SLIDESHOWS 
Slideshows can display a number of different images  (or other HTML content) within the same space  on a given page.They allow more content to be displayed within a limited amount of space. 

 1. React: Script triggered when the page loads 
 2. Access: Get each slide from the slideshow 
 3. Modify: Only show the first slide (hide others) 
 4. Program: Set a timer: when to show next slide 
 5. Modify: Change which slide is shown 
 6. React: When user clicks button for different slide 
 7. Program: Determine which slide to show 
 8. Modify: Show the requested slide

### FORMS 

 Validating forms (checking whether they have been  filled in correctly) is important when information is supplied by users. JavaScript lets you alert the user if mistakes have been made. 
  1. React: User presses the submit button when they have entered their name 
  2. Access: Get value from form field 
  3. Program: Check that the name is long enough 
  4. Modify: Show a warning message if the name is not long enough

### RELOAD PART OF PAGE 

  You might not want to force visitors to reload the  content of an entire web page, particularly if you only need to refresh a small portion of a page. Just reloading a section of the page can make a site feel like it is faster to load and more like an application. 
   1. React: Script triggered when user clicks on link 
   2. Access: The link that they clicked on 
   3. Program: load the new content that was requested from that link 
   4. Access: Find the element to replace in the page 
   5. Modify: Replace that content with the new content 

### FILTERING DATA 

   If you have a lot of information to display on a page, you can help users find information they need by providing filters. 

**variable:its somthing that stores values**
**using the `var` keyword the only way to declare a JavaScript variable.**
All JavaScript variables must be identified with unique names.These unique names are called ***identifiers***.

+ The general rules for constructing names for variables (unique identifiers) are:

  1. Names can contain letters, digits, underscores, and dollar signs.
  2. Names must begin with a letter
  3. Names are case sensitive (y and Y are different variables)
  4. Reserved words (like JavaScript keywords) cannot be used as names



| Data Types    |              Example                      | 
| :---          |             :----:                        |            
|    String     |     'hello', "hello world!"               | 
|    Number     |            3, 3.234                       | 
|    Boolean    |          true and false                   | 
|    Object     |         let student = { };                | 





	
	
| Code  |      Result        | 
| :---  |      :----:        |
|  \b   |Backspace           | 
|  \f   |Form Feed           | 
|  \n   |New Line            | 
|  \r   |Carriage Return     | 
|  \t   |Horizontal Tabulator| 
|  \v   |Vertical Tabulator  | 


#### OPERATORS 

Expressions rely on things called operators; they allow programmers to create a single value from one or more values. 
  
  
 **Arithmatic Operators**
| Operator  | Description   | 
| :---      |   :----:      |
|   +       |Addition       | 
|   -       |Subtraction    | 
|   *       |Multiplication | 
|   **      |Exponentiation | 
|   /       |Division       | 
|   %       |ModulusVer     | 
|   x++     |x+1            | 
|   x--     |x-1            | 
|   x+=1    |x=x+1          | 
|   x-=1    |x=x-1          | 



**Comparison Operators**
| Operator  |        Description                 | 
| :---      |          :----:                    |
|   ==      |	equal to                           | 
|   ===     |equal value and equal type          | 
|   !=      |	not equal                          | 
|   !==     |not equal value or not equal type	 | 
|   >       |greater than	                       | 
|   <       |less than	                         | 
|   >=      |greater than or equal to	           | 
|   <=      |less than or equal to               | 
	


**JavaScript Comments**



Single line comments start with //.



Multi-line comments start with /* and end with */.




### COMPUTERS CREATE MODELS OF THE WORLD USING DATA


+ **OBJECTS & PROPERTIES :**
OBJECTS (THINGS)In computer programming, each physical thing in the world can be represented as an object.

+ **PROPERTIES (CHARACTERISTICS)** Programmers call these characteristics the properties of an object.

+ **EVENTS:**
In the real world, people interact with objects. These interactions can change the values of the properties in these objects.

+ **METHODS**
Methods represent things people need to do with objects. They can retrieve or update the values of an object's properties.
HOW HTML, CSS,& JAVASCRIPT FIT TOGETHER


 **Functions**
+ A JavaScript function is a block of code designed to perform a particular task.

+ A JavaScript function is executed when "something" invokes it (calls it).



`function name(parameter1, parameter2, parameter3) {`

  `// code to be executed`

`}`


+ A JavaScript function is defined with the function keyword, followed by a **name**, followed by parentheses ().


+ Function **names**can contain letters, digits, underscores, and dollar signs (same rules as variables).


+ The parentheses may include parameter names separated by commas:(**parameter1**, **parameter2**, ...)


+ The code to be executed, by the function, is placed inside curly brackets: {}


#### parameters VS arguments

+ Function **parameters** are listed inside the parentheses () in the function definition.


+ Function **arguments** are the values received by the function when it is invoked.





### HOW HTML, CSS,& JAVASCRIPT FIT TOGETHER

+  Web developers usually talk about three languages that are used to create web pages: HTML, CSS, and JavaScript.

+ Where possible, aim to keep the three languages in separate files, with the HTML page linking to CSS and JavaScript files.

+ Each language forms a separate layer with a different purpose. Each layer, from left to right. builds on the previous one.

  1. CONTENT LAYER . html files This is where the content of the page lives. The HTML gives the page structure and adds semantics.

  2. PRESENTATION LAYER . css files The CSS enhances the HTML page with rules that state how the HTML content is presented (backgrounds, borders, box dimensions, colors, fonts, etc.).

  3. BEHAVIOR LAYER .js files This is where we can change how the page behaves, adding interactivity. We will aim to keep as much of our JavaScript as possible in separate files.




    