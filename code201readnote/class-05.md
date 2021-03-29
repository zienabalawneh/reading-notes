# HTML Images; CSS Color & Text
# **HTML BooK**
## Chapter 5: “Images”

#### Images & Image Size 


`<img src="img_chania.jpg" alt="Flowers in Chania">`


`<img src="img_girl.jpg" alt="Girl in a jacket" width="500" height="600">`

+ The HTML <img> tag is used to embed an image in a web page.

+ The <img> tag is empty, it contains attributes only, and does not have a closing tag.

+ The <img> tag has two required attributes:

   1. src - Specifies the path to the image
   2. alt - Specifies an alternate text for the image
   3. Width
   4. height
   5. align

 #### Place Images in Your Code

   1. before a paragraph:
    The paragraph starts on a new line after the image

    `<img scr="the path" alt="description"/><p>before a paragraph</p>`

   2. inside the start of a paragraph:
    The first row of text aligns with the bottom of the image.

    `<p><img src="the path" alt="the alt"/>inside the start of a paragraph</p>`

   3. in the middle of a paragraph:
    The image is placed between the words of the paragraph that it appears in.

    `<p>in the middle<img src="path" alt="alt"/>of a paragraph</p>`

#### Aligning Images Horizontally
1. left:
`<img src="images/bird.gif" alt="Bird" align="left" />`
2. right:
`<img src="images/bird.gif" alt="Bird" align="right" />`
3. top:
`<img src="images/bird.gif" alt="Bird"  align="top" />`
4. middle:
`<img src="images/bird.gif" alt="Bird" align="middle" />`
5. bottom:
`<img src="images/bird.gif" alt="Bird" align="bottom" />`

#### Three Rules for Creating Images
 1. Save images in the right format
 2. Save images at the right size
 3. Use the correct resolution

#### Tools to Edit & Save Images
+  Adobe Photoshop
+ Adobe Fireworks
+ Pixelmator
+ PaintShop Pro
+ Paint.net

#### Figure and Figure Caption

`<figure>`

+ You can have more than one image inside the `<figure>`element as long as they all share the same caption.

`<figcaption>`

+ to allow web page authors to add a caption to an image.




***Photographs are best saved as JPEGs; illustrations or logos that use flat colors are better saved as GIFs.***

## Chapter 11: “Color”
`color : red;`
`background-color : red;`

**Color can really bring your pages to life.**

  
 ![color1](https://www.w3schools.com/colors/img_colormap.gif)
 ![color](https://ishadeed.com/assets/color-css/color-wheel-1.jpg)
 ![color](https://www.allaboutof.com/wp-content/uploads/2018/07/color-codes-1.jpg)


 1. **RGB** Values Values for red, green, and blue are expressed as numbers between 0 and 255

2. **Hex** Codes Hex values represent values for red, green, and blue in hexadecimal code.

3. Color **Names Colors** are represented by predefined names. However, they are very limited in number.

## Chapter 12: “Text”

#### Typeface terminology:

`font-family : Arial, verdana,sans-serif;`

 1. Sans-Serif
 2. Serif
 3. Monospace
 4. Cursive
 5. Fantasy

#### Size of Type:

`font-size: 1.3em;`

1. pixels
2. percentages
3. ems
#### font-weight
 `font-weight:bold;`

1. bold
2. normal

#### font-style

`font-style:italic;`

1. italic
2. oblique
3. normal

#### text-transform

`text-transform : uppercase;`
 
 1. uppercase
 2. lowercase
 3. capitalize

#### text-decoration

   ` text-decoration : underline;`
   1. none
   2. underline
   3. overline
   4. line-through
   5. blink

#### letter-spacing, word-spacing 

` letter-spacing:0.2 em;`

`word-spacing: 1em;`


#### Text-align

`text-align: left;`

1. left
2. right
3. center
4. justify

#### vertical-align


`vertical-align: text-bottom;`

1. baseline
2. top
3. text-top
4. middle
5. bottom
6. text-bottom

#### text-shadow

`text-shadow: 1px 1px 0px #000000;`

#### styling links

`a:link{`
    `color:deeppink;`
    `text-decoration:none;`
`}`

# **JPEG vs PNG vs GIF**

+ Use **JPEG**format for all images that contain a **natural scene** or**photograph**where **variation** in colour and **intensity is** smooth.

+  Use **PNG** format for any image that needs transparency or for images with text & objects with sharp contrast edges like **logos**.

+  Use **GIF** format for images that contain **animations**.

#### Compression

+ Almost all forms of data that we see on the internet are compressed to reduce the size of data and ensure faster transmission. Choosing the correct format and compression is a major factor that determines image size.

1. **JPEG** is a lossy compression specification that takes advantage of human perception. It can achieve compression ratios of 1:10 without any perceivable difference in quality.JPEG images are best suited for photographs and paintings of natural scenes where the variations in colour and intensity are smooth.

2. **PNG** is a lossless image format No data is lost during compression and no compression artefacts are introduced in the image. For this reason, a PNG image would retain higher quality than an image than JPEG and would look a lot sharper, it would also occupy more space on the disk. This makes it unsuitable for storing or transferring high-resolution digital photographs but a great choice for images with text, logos and shapes with sharp edges.

3. **GIF** is also a lossless image format that uses LZW compression algorithm. It was favoured over PNG for simple graphics in websites in its early days because the support of PNG was still growing. Given that PNG is now supported across all major devices and that PNG compression is about 5–25% better than GIF compression, GIF images are now mainly used only if the image contains animations.


#### Transparency
transparency indicates something that is completely invisible. Logos and icons often need to be placed on backgrounds with variable colours. Hence it is desirable, that the background of these logos and icons is made transparent so that a single image can be used over multiple background variations.

**JPEG** images don’t support transparency and are hence not usable for such cases.

**PNG** images support transparency in two ways:
1. inserting an alpha channel that allows partial transparency 
2. declaring a single colour as transparent

**GIF** images support transparency by declaring a single colour in the colour palette as transparent

#### Colours

**JPEG** images can support around 16 million colours. This is what makes them suitable for storing images of natural scenes.

**PNG** images mainly have two modes — PNG8 and PNG24. PNG8 can support upto 256 colours whereas PNG24 can handle upto 16 million colours like a JPEG image.

**GIF** images are limited to 256 colours. If index transparency is used, then one of these 256 colours is assigned as transparent and the remaining 255 are used for other colours.


#### Animation
+ animation in this case, refers to any change or movement in the image.

+ Of these 3 formats, only **GIF** supports animation. 