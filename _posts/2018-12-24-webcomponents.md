---
layout: single
title:  "Web Components - For Micro-frontends and Re-usable components"
tags:
  - Webcomponents
  - Javascript
  - Polymer
---

# Web Components - For Micro-frontends and Re-usable components
Let's build em all!

## What are Web Components?
> Web components are a set of web platform APIs that allow you to create new custom, reusable, encapsulated HTML tags to use in web pages and web apps.

Source: https://www.webcomponents.org/introduction


> Web Components is a suite of different technologies allowing you to create reusable custom elements — with their functionality encapsulated away from the rest of your code — and utilize them in your web apps.

Source: https://developer.mozilla.org/en-US/docs/Web/Web_Components

> (Web) Components are the building blocks of modern web applications.

Source: https://developers.google.com/web/fundamentals/web-components/


  ![WebComponents Parts](https://cdn-images-1.medium.com/max/800/0*RkhhR4vWy4O9nemq.png)

 
  [Another Blog With Drawing](https://medium.freecodecamp.org/use-web-components-to-create-gradient-transitions-f9aad648824a)

Web Components are the result of an effort by the web community to have common specs for these 'building blocks of the web'
There are two broad categories in which this can be used:
* For building __Micro-frontends__ - These are small but contains detailed business logic
* For building __Re-usable Components__ - These rarely contain any business logic. Highly targeted and re-usable components


## Basic Concepts
To understand and discuss the 3 technologies that are used to make Web components a thing, we need to first see what happens usually when an HTML page is rendered.


...once the server approves your request, the server sends the website files in chunks - called data packets.
These packets are then assembled by your browser into a complete website and display it to us.

These chunks are basically out HTML, CSS, and JavaScript, though other technologies are also available.
The browser steps include:
* Process HTML markup and build the DOM tree.
* Process CSS markup and build the CSSOM tree.
* Combine the DOM and CSSOM into a render tree.
* Run layout on the render tree to compute geometry of each node.
* Paint the individual nodes to the screen.

JavaScript is a dynamic language that runs in a browser and allows us to alter just about every aspect of how the page behaves:
* JavaScript can query and modify the DOM and the CSSOM.
* JavaScript execution blocks on the CSSOM.
* JavaScript blocks DOM construction unless explicitly declared as async.

Note: This page is usually what I refer to as the base: [Web Technologies](https://developer.mozilla.org/en-US/docs/Web)

I would recommend every developer, associated with Web development, to revisit this page every 3 months, else the dark side WINS!

## What makes up Web components
So the suit that makes web components possible is
* Custom Elements - JavaScript APIs to define custom elements and tell it to the browser.

* ShadowDOM - so that Scripting and Styling without fear of collisions

* HTML templates - \<template\> and \<slot\> elements


## Getting Started
To create a Components, broadly here are the steps we would take
* Create a Class - put your logic
* Tell the browser about this new Custom Element
* Optional: attach Shadow DOM
* Optional: define a template and then attach
* Use the new Component!


To build we have a lot of options, thanks to the uber-vibrant JavaScript community,
Our options:
* Using native JavaScript. Best source Web components by [Google Developer docs](https://developers.google.com/web/fundamentals/web-components/)
* [Polymer - Google's web components framework](https://www.polymer-project.org/)
* [Angular Elements](https://angular.io/guide/elements)
* [Hybrids](https://github.com/hybridsjs/hybrids) is a UI library for creating Web Components with simple and functional API
* [LitElement](https://lit-element.polymer-project.org/) - A simple base class for creating fast, lightweight web components
* [Slim.js](http://slimjs.com/#/getting-started) is a lightweight web component authoring library

## Time to build
In this session, we will build one using - Pokemon!!!
[Shared codebase on github for kaaro-pokemon webcomponent](https://github.com/karx/webcomponents/tree/master/Pokemon)


## Good reads/links:
* [Custom elements everywhere](https://custom-elements-everywhere.com/)
* [Custome Element Reaction Diagram](https://andyogo.github.io/custom-element-reactions-diagram/)
* [w3 specs custom elements](https://w3c.github.io/webcomponents/spec/custom/)
* [Github Issue](https://github.com/w3c/webcomponents/issues)
* [Google model viewer](https://developers.google.com/web/updates/2019/02/model-viewer)
* [history of web](https://home.cern/science/computing/birth-web/short-history-web)


[Link to slides @MozillaPunjab LPU on 24th March ](https://slides.com/kartikarora-1/web-componentss)
[Link to GitHub repo used](http://github.com/karx/webcomponents)