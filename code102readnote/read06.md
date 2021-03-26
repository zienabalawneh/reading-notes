# Design web pages with CSS

+ What is CSS?

  **Cascading Style Sheets (CSS)** is used to format the layout of a webpage and to make your web pages more attractive(Controlling the design of the them using CSS).


  With CSS, you can control the color, font, the size of text, the spacing between elements, how elements are positioned and laid out, what background images or background colors are to be used, different displays for different devices and screen sizes, and much more!


## Using CSS
+ CSS can be added to HTML documents in 3 ways:

1. **Inline** - by using the style attribute inside HTML elements

2. **Internal** - by using a `<style>`element in the `<head>` section

3. **External** - by using a `<link>` element to link to an external CSS file


   ### Inline CSS
     + An inline CSS is used to apply a unique style to a single HTML element.

     + An inline CSS uses the style attribute of an HTML element.
     
     + Inline elements flow within the text and do not start on a new line . Examples include `<b> , <i>,<img>,<em>,<span>`.

       ` <h1 style="color:blue;"> A Blue Heading </h1>`

   ### Internel CSS
   + An internal CSS is used to define a style for a single HTML page.

   + An internal CSS is defined in the  `<head> ` section of an HTML page, within a  `<style> ` element.

    `<style> `
     `body {background-color: powderblue;} ` 
      `h1   {color: blue;} `
    `</style>`

   ### External CSS
   + An external style sheet is used to define the style for many HTML pages.

     `<link rel="stylesheet" href="styles.css">`


   ### CSS Colors, Fonts and Sizes


  + The CSS color property defines the text color to be used.

  + The CSS font-family property defines the font to be used.

  + The CSS font-size property defines the text size to be used.




     Use the HTML style attribute for inline styling

     Use the HTML `<style>` element to define internal CSS

     Use the HTML `<link>` element to refer to an external CSS file

     Use the HTML `<head>` element to store `<style>` and `<link>` elements

     Use the CSS color property for text colors

     Use the CSS font-family property for text fonts

     Use the CSS font-size property for text sizes

     Use the CSS border property for borders

     Use the CSS padding property for space inside the border

     Use the CSS margin property for space outside the border
      
      



       ![css](https://e7.pngegg.com/pngimages/606/516/png-clipart-cascading-style-sheets-computer-icons-css3-world-wide-web-text-logo.png)


      niversal selector `*{} `target all elements on the page

      Type selector` h1,h2,h3 {}` targets the `<h1>,<h2>,<h3>`

      Class selector `.note{}`

      Id selector` #introduction{}`

      Child selector `li>a{}`

      Descendant selector p `a {}`


      ## ch 11
      
      **Color can really bring your pages to life.**

   

    ![color1](https://www.w3schools.com/colors/img_colormap.gif)
    ![color](https://ishadeed.com/assets/color-css/color-wheel-1.jpg)

    1. **RGB** Values Values for red, green, and blue are expressed as numbers between 0 and 255

    2. **Hex** Codes Hex values represent values for red, green, and blue in hexadecimal code.

    3. Color **Names Colors** are represented by predefined names. However, they are very limited in number.

      
