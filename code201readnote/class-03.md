# HTML Lists, CSS Boxes, JS Control Flow
## **HTML book**
### Chapter 3: “Lists”
+ HTML lists allow web developers to group a set of related items in lists. HTML provides us with 
three different types:

 1. Unordered HTML List:
 An unordered list starts with the `<ul>` tag. Each list item starts with the `<li>` tag.

2. Ordered HTML List:
 An ordered list starts with the `<ol>` tag. Each list item starts with the` <li> `tag.

3. HTML Description Lists(Definition lists):
  A description list is a list of terms, with a description of each term.The` <dl>` tag defines the description list, the `<dt> `tag defines the term (name), and the `<dd> `tag describes each term

### Chapter 13: “Boxes” 

+ we can set/change many properties that affect the appearance of that boxes so we will do :

   1. changing the dimenstion of boxes .

   2. creating borders around boxes.

   3. set margins and padding for the boxes .

   4. show and hide the boxes .


#### Box Dimensions

`div.box {`
`height: 300px;`
`width: 300px;`
`background-color: #bbbbaa;}`

#### Limiting Width
 **min-width , max-width** page designs expand and shrink to fit the size of the user's screen


#### limiting height
**min-height , max-height** the same way for it as the limiting width.

#### Overflowing Content

The overflow property tells the browser what to do if the content contained within a box is larger than the box itself. It can have one of two values:
1. hidden:
This property simply hides any extra content that does not fit in the box.

2. scroll:
This property adds a scrollbar to the box so that users can scroll to see the missing content.

#### Border, Margin & Padding


##### CSS Border Style

 `border-style: dotted;`

` border-style: outset;`

+ **The border-style**property specifies what kind of border to display.The following values are allowed:

 1. dotted - Defines a dotted border
 2. dashed - Defines a dashed border
 3. solid - Defines a solid border
 4. double - Defines a double border
 5. groove - Defines a 3D grooved border. The effect depends on the border-color value
 6. ridge - Defines a 3D ridged border. The effect depends on the border-color value
 7. inset - Defines a 3D inset border. The effect depends on the border-color value
 8. outset - Defines a 3D outset border. The effect depends on the border-color value
 9. none - Defines no border
 10. hidden - Defines a hidden border




##### CSS Border Width


  `border-width: 5px;   ` 

`  border-width: medium; `


+ **The border-width** property specifies the width of the four borders.
+ The width can be set as a specific size (in px, pt, cm, em, etc) or by using one of the three pre-defined values: thin, medium, or thick


##### CSS Border Color

  `border-color: red;`

 ` border-color: rgb(255, 0, 0);   `


+ **The border-color** property is used to set the color of the four borders.

 1. name - specify a color name, like `red`
 2. HEX - specify a HEX value, like `#ff0000`
 3. RGB - specify a RGB value, like `rgb(255,0,0)`
 4. HSL - specify a HSL value, like `hsl(0, 100%, 50%)`



 ##### shorthand border 

` border: 5px solid red;`

`border-left: 6px solid red;`


 + To shorten the code, it is also possible to specify all the individual border properties in one property(to change all of what we said in one property).



#### Padding

` padding: 70px;`

 `padding-top: 50px;`

 `padding-right: 30px;`

 `padding-bottom: 50px;`

 `padding-left: 80px;`

+ Padding is used to create space around an element's content, inside of any defined borders.
+ The CSS padding properties are used to generate space around an element's content, inside of any defined borders.

#### Margin

`margin: 50px;`

`margin-top: 100px;`

`margin-bottom: 100px;`

`margin-right: 150px;`

`margin-left: 80px;`



+ Margins are used to create space around elements, outside of any defined borders.
+ The CSS margin properties are used to create space around elements, outside of any defined borders.

#### Centering Content


`text-align: center;`

+ The` <center>` tag was used in HTML4 to center-align text.

#### Change Inline/Block


`display: inline; `


1. inline :This causes a block-level element to act like an inline element.
2. block: This causes an inline element to act like a block-level element.
3. inline-block:This causes a block-level element to flow like an inline element, while retaining other features of a block-level element.
4. none: This hides an element from the page



#### Hiding Boxes visibility

`visibility: hidden;`

1. hidden:This hides the element.
2. visible:This shows the element.

#### Box Shadows


+ The box-shadow property attaches one or more shadows to an element.
1. Horizontal offset
2. Vertical offset
3. Blur distance
4. Spread of shadow




#### Border Images
 
` border-image: url(border.png) 30 round;`


+ With the CSS border-image property, you can set an image to be used as the border around an element.



#### Rounded Corners


`  border-radius: 25px;`


+ With the CSS **border-radius** property, you can give any element "rounded corners".


## **JS book**

### Chapter 2: “Basic JavaScript Instructions”
A script is a series of instructions that the computer can follow in order to achieve a goal. 

**JavaScript** allows you to make web pages more interactive by modifying the contents, reflecting that modification on the web page, and responding to what the user is doing.


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



#### Array
An array is a special type of variable. It doesn't just store one value; it stores a list of values.

this exapmle from the book :

`var colors;`

`colors ['white', 'black', ' custom'];`

`var el document.getElementByld('col ors');`

`el.textContent = col ors[O]; `

	
	
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






**JavaScript Comments**



Single line comments start with //.



Multi-line comments start with /* and end with */.


## Chapter 4: Decisions and Loops

**Conditional statements** control behavior in JavaScript and determine whether or not pieces of code can run(Conditional statements allow your code to make decisions about what to do next).

+ There are multiple different types of conditionals in JavaScript including:

  “If” statements: where if a condition is true it is used to specify execution for a block of code.

  “Else” statements: where if the same condition is false it specifies the execution for a block of code.

  “Else if” statements: this specifies a new test if the first condition is false.




## There are three types of loop: for, while, and  do ... while. Each repeats a set of statements.
1. **for** - loops through a block of code a number of times

    **The for loop has the following syntax:**

      For (statement 1; statement 2; statement 3) {

         // code block to be executed

            }

+ **Statement 1** is executed (one time) before the execution of the code block.

+ **Statement 2** defines the condition for executing the code block.

+ **Statement 3** is executed (every time) after the code block has been executed.
 
 
2. **while** - loops through a block of code while a specified condition is true
      
    **The while loop has the following syntax:**

     while (condition) {

    // code block to be executed
          }



3. **do/while** - also loops through a block of code while a specified condition is true(the loop will always be executed at least once, even if the condition is false, because the code block is executed before the condition is tested).

    **The do_while loop has the following syntax:**

      do {

    // code block to be executed
    
    }
    while (condition);