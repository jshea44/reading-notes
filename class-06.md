# Readings: Problem Domain, Objects, and the DOM
This is an oveview of objects in Javascript as well as how Javascript and the DOM work together to manipulate web pages. 

## JavaScript Object Basics
  1. An object is a collection of things that are related. These are things that describe what that object is or what it can do. For instance, in this collection, you could have data describing what the object looks like, maybe long hair, brown hair, four legs, two eyes, etc. You could also have data that describes what this object can do such as bark, pant, run, eat, rollover. 
  2. An advantage would be if you have multiple related pieces of data, you could place them all in an object. If you had data such as name,  age, a function of a trick, a function for speak, then all of that could be placed into an object that might be called dog.
  3. Objects differ from arrays in the sense that arrays can only be accessed by their location in the way of an index. Objects contain key:value pairs. You can access a value in an object by getting ahold of its key either by bracket notation or dot notation
  4. Bracket notation would be used if the property name is held in a variable. You couldn't access it with dot notation at that point.
  5. `this` refers to the object itself. In terms of the example, `this` is refering to dog. The advantage is that when you are creating constructors, in which case you are creating multiple objects from the same blueprint if you will, `this` doesn't have to change inside of the methods. `this` could refer to whatever object name you gave that was made form the constructor.

## Introduction To The DOM
  1. DOM stands to Document Object Model. It creates a sort of copy of your HTML into an object or multiple objects that can then be manipulted by javascript.
  2. The DOM is independent from javascript. It's a WebAPI that can work with javascript, but it can in fact use other languages such as python. Javascript uses the DOM to access the webpage and manipulated it. The document as a whole is apart of the DOM.
## Things I want to know more about
