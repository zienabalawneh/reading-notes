# CSS Transforms, Transitions, and Animations

# CSS Transforms


![Transforms](https://user.oc-static.com/upload/2019/01/18/15478200836531_pt02ch02_06_transPer_v001.gif)
+ The transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.


## Transform Syntax
+ The actual syntax for the transform property is quite simple, including the transform property followed by the value. The value specifies the transform type followed by a specific amount inside parentheses.


`div {`
 ` -webkit-transform: scale(1.5);`

   ` -moz-transform: scale(1.5);`

   `-o-transform: scale(1.5);`

   `transform: scale(1.5);`
`}`

## 2D Transforms

Elements may be distorted, or transformed, on both a two-dimensional plane or a three-dimensional plane. Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes. Three-dimensional transforms work on both the x and y axes, as well as the z axis. These three-dimensional transforms help define not only the length and width of an element, but also the depth.

1. 2D Rotate

` transform: rotate(20deg);`

2. 2D Scale

` transform: scale(1.25);`

3. 2D Translate

`transform: translate(-10px, 25%);`


4. 2D Skew

 `transform: skew(5deg, -20deg);`
 
 
5. Combining Transforms

 `transform: skew(10deg, 20deg) translateX(20px);`

6. Transform Origin

  + `transform: scale(.5);`

    `transform-origin: 100% 100%;`


  + `transform: skewX(20deg);`

   `transform-origin: top left;`



## 3D Transforms

+ Working with two-dimensional transforms we are able to alter elements on the horizontal and vertical axes, however there is another axis along which we can transform elements. Using three-dimensional transforms we can change elements on the z axis, giving us control of depth as well as length and width.

1. 3D Rotate

 ` transform: perspective(200px) rotateZ(45deg);`

2. 3D Scale

  `transform: perspective(200px) scaleZ(.25) rotateX(45deg);`

3. 3D Translate

  `transform: perspective(200px) translateZ(50px);`

# Transitions & Animations


## Transitions

+ As mentioned, for a transition to take place, an element must have a change in state, and different styles must be identified for each state. The easiest way for determining styles for different states is by using the `:hover`, `:focus`, `:active`, and `:target` pseudo-classes.



## Transitional Properties

+ A handful of the more popular transitional properties include the following

    + background-position

    + border-color



## Transition Duration

` transition-duration: .2s, 1s;`

## Transition Timing

  `transition-timing-function: linear, ease-in;`

## Transition Delay

  `transition-delay: 0s, 1s;`



## Shorthand Transitions

  `transition: background .2s linear, border-radius 1s ease-in 1s;`



# Animations

## Animations Keyframes


`@keyframes slide {`

 ` 0% {`

   `left: 0;`

   `top: 0;`

  `}`

  `50% {`

   `left: 244px;`

   `top: 100px;`

  `}`

  `100% {` 

  `left: 488px;` 

   `top: 0;` 

  `}`
`}`





## Animation Name

`animation-name: slide;`


## Animation Duration, Timing Function, & Delay


  `animation-duration: 2s;`

  `animation-timing-function: ease-in-out;`

  `animation-delay: .5s;`



## Animation Iteration

 ` animation-iteration-count: infinite;`

## Animation Direction

  `animation-direction: alternate;`

## Animation Play State

  `animation-play-state: paused;`



# 8 SIMPLE CSS3 TRANSITIONS THAT WILL WOW YOUR USERS


1. Fade in

2. Change color

3. Grow & Shrink

4. Rotate elements

5. Square to circle

6. 3D shadow

7. Swing

8. Inset border