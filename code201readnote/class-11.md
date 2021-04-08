# Chapter 16: “Images”

## Controlling sizes of images in CSS


`<img src="paris.jpg" alt="Paris" width: 500px; height: 500px;>`

+ you can control the size of an image using the width and height properties in CSS.




## Centering images using in CSS


`<img src="paris.jpg" alt="Paris" style="display: block; margin: 0px auto;">`


## Aligning images using in CSS


`<img src="paris.jpg" alt="Paris" style="float: left;margin-right: 10px;">`

## Background Images


`background-image: url("img/paris.jpg");`

+ The background-image property allows you to place an image behind any HTML element. 




## background-repeat

 `background-repeat: repeat;`

1. repeat
The background image is repeated both horizontally and vertically .

2. repeat-x
The image is repeated horizontally only .

3. repeat-y
The image is repeated vertically only .


4. no-repeat
The image is only shown once.The background-attachment property specifies whether a background image should stay in one position or move as the user scrolls up and down the page. It can have one of two values:

  1. fixed

       `background-repeat: no-repeat;`

       `background-attachment: fixed;`

     The background image stays in the same position on the page.

  2. scroll

       `background-repeat: no-repeat;`

       `background-attachment: scroll;`

     The background image moves up and down as the user scrolls up and down the page.

## background-position

`background-position: left top;`

 1. left top

 2. left center

 3. left bottom

 4. center top

 5. center center

 6. center bottom

 7. right top

 8. right center

 9. right bottom

## shorthand background

`background: #ffffff url("images/tulip.gif") no-repeat top right`


## Gradients


`background-image: -webkit-linear-gradient(#336666, #66cccc); `





# Chapter 19: “Practical Information”

## Search Engine Optimization (SEO)

![SEO](https://www.oberlo.com/media/1603954182-seo-article-header.png?fit=max&fm=jpg&w=1824)

![SEO](https://hurricaneddm.com/wp-content/uploads/2019/10/search-engine-optimization-img-02.png)

+ **Search engine optimization (or SEO)** is the practice of trying to help your site appear nearer the top of search engine results when people look for the topics that your website covers.

+ **On-page techniques** are the methods you can use on your web pages to improve their rating in search engines.


+ **Off-Page Techniques** getting other sites to link to you is just as important as on-page techniques. Search engines help determine how to rank your site by looking at the number of other sites that link to yours.



## On-page SEO

![On-page SEO](https://www.attorneyseoranking.com/wp-content/uploads/2015/04/on-page-seo.png)

1. Page Title

2. URL / Web Address

3. Headings

4. Text

5. Link Text

6. Image Alt Text

7. Page Descriptions


## Domain Names & Hosting

+ In order to put your site on the web you will need a domain name and web hosting

1. Domain Names

Your domain name is your web address (e.g. google.com or bbc.co.uk). There are many websites that allow you to register domain names. Usually you will have to pay an annual fee to keep that domain name.

2. WEB Hosting

So that other people can see your site, you will need to upload it to a web server. Web servers are special computers that are constantly connected to the Internet. They are specially set up to serve web pages when they are requested.


## FTP & Third Party Tools

To transfer your code and images from your computer to your hosting company, you use something known as File Transfer Protocol.



![FTP](https://lh3.googleusercontent.com/proxy/_wKlvSuFTJaeMfYLVTck5uQQSGgrBqAYDt3bM18goy5yv2iGH5y5jG3oMbwmwh2-992wljbrv1rbZ5yIvtRn-7h4f7dsnWF-UZYr-3GC2rz9)


**The File Transfer Protocol (FTP)** is a standard communication protocol used for the transfer of computer files from a server to a client on a computer network. FTP is built on a client–server model architecture using separate control and data connections between the client and the server.


# Video and audio content

1. Video

`<video width="320" height="240" controls>`

 ` <source src="movie.mp4" type="video/mp4">`

  `<source src="movie.ogg" type="video/ogg">`

  Your browser does not support the video tag.
`</video>`



2. Audio 

`<audio controls>`
  `<source src="horse.ogg" type="audio/ogg">`
  `<source src="horse.mp3" type="audio/mpeg">`
  Your browser does not support the audio element.
`</audio>`



