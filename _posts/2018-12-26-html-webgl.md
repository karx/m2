---
layout: single
title:  "HTML Canvas  - Using WebGL"
tags:
  - Canvas
  - WebGL
  - Javascript
  - Web API
  - HTML
---
## WebGL
Things might get a little bit math-y in the midst of this, but why else did you pay so much money to learn about Matrices and Calculus.

The day is here.
But before we are able to get to the fun stuff. Lets first discuss what would we be trying to do, the current effort we did regarding the same, and then conclude by starting with WebGL.

## Aim
Our aim, simply put is
> to have mathematical/computational manifestations of our visualizations!

Or to have tools, skills and knowledge that we could use to draw/depict any visualization I want.

## Current Efforts
So now is the time to first tell you about OpenGL. You must have seen/heard about it. To define, 
> OpenGL is* a specification describing an abstract API for drawing 2D and 3D graphics.

OpenGL is an evolving API specification, regularly released by the Khronos Group, each of which extends the API to support various new features. 
In theory, all the implementation of these specifications can be done using entirely software. 

Then, now we have something known as **WebGL**. Now WebGL is a JavaScript API for doing these fun stuff, based on OpenGL ES 3.0. Now OpenGL ES is basically a mobile optimised version of OpenGL, but lets now worry about that. 
WebGL now. Let's talk and understand more about WebGL before we move on. 

## Getting started with WebGL
I would recommend reading through the following document[Getting started with WebGL](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API/Tutorial/Getting_started_with_WebGL)



## Time to build
If you are following along, now checkout attempt6 folder of out kCanvas repository:


[Attempt 6](https://github.com/karx/kCanvas/tree/master/attempt6) closely follows this tutorial from MDN

## Ecosystem
WebGL itself might be too tedious to directly use without having a bunch of helper functions. three.js, BabylonJS, etc are examples of such libraries.

