## [Back to Homepage](https://pengchen11.github.io/reading-notes/readme.md)

# CSS Animations
CSS allows animation of HTML elements without using JavaScript or Flash!

## What are CSS Animations?  
An animation lets an element gradually change from one style to another.  

You can change as many CSS properties you want, as many times you want.  

To use CSS animation, you must first specify some keyframes for the animation.  

Keyframes hold what styles the element will have at certain times.

## The @keyframes Rule  

When you specify CSS styles inside the @keyframes rule, the animation will gradually change from the current style to the new style at certain times.  

To get an animation to work, you must bind the animation to an element.  

The following example binds the "example" animation to the ```<div>``` element. The animation will last for 4 seconds, and it will gradually change the background-color of the ```<div>``` element from "red" to "yellow":
```
/* The animation code */
@keyframes example {
  from {background-color: red;}
  to {background-color: yellow;}
}

/* The element to apply the animation to */
div {
  width: 100px;
  height: 100px;
  background-color: red;
  animation-name: example;
  animation-duration: 4s;
}
```

## Delay an Animation
The animation-delay property specifies a delay for the start of an animation.

The following example has a 2 seconds delay before starting the animation:
```
div {
  width: 100px;
  height: 100px;
  position: relative;
  background-color: red;
  animation-name: example;
  animation-duration: 4s;
  animation-delay: 2s;
}
```
## CSS Animation Properties
The following table lists the @keyframes rule and all the CSS animation properties:
| Property |	Description |
|---|:---|
|@keyframes	|Specifies the animation code|
|animation	|A shorthand property for setting all the animation properties|
|animation-delay	|Specifies a delay for the start of an animation|
|animation-direction	|Specifies whether an animation should be played forwards, backwards or in alternate cycles|
|animation-duration	|Specifies how long time an animation should take to complete one cycle|
|animation-fill-mode |Specifies a style for the element when the animation is not playing (before it starts, after it ends, or both)|
|animation-iteration-count	|Specifies the number of times an animation should be played|
|animation-name	|Specifies the name of the @keyframes animation|
|animation-play-state	|Specifies whether the animation is running or paused|
|animation-timing-function	|Specifies the speed curve of the animation|

# CSS Transitions
## How to Use CSS Transitions?
To create a transition effect, you must specify two things:

the CSS property you want to add an effect to
the duration of the effect
Note: If the duration part is not specified, the transition will have no effect, because the default value is 0.

The following example shows a 100px * 100px red <div> element. The <div> element has also specified a transition effect for the width property, with a duration of 2 seconds:
```
div {
  width: 100px;
  height: 100px;
  background: red;
  transition: width 2s;
}
```
Delay the Transition Effect
The transition-delay property specifies a delay (in seconds) for the transition effect.

The following example has a 1 second delay before starting:  
Example
```
div {
  transition-delay: 1s;
}
```
# Transforms Methods
With the CSS transform property you can use the following 2D transformation methods:

- translate()
- rotate()
- scaleX()
- scaleY()
- scale()
- skewX()
- skewY()
- skew()
- matrix()


