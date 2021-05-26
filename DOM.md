
<h1 align="center">DOM</h1>

DOM stands for Document Object Model. Every website even the most basic ones consists an HTML and CSS to which the browser creates a representation of the document known as DOM. This document enables the developer to access and manipulate the elements and styles of a website to make it more interactive for the user with the help of Javascript.
<br>
<br>
So, in order to make an HTML document more interactive and dynamic, the javascript‌‌ needs to access the contents of the document and it also needs to know when the user is interacting with it.‌‌ DOM does this by communicating with the browser and by using the properties, methods, and events in the interface called the DOM.
<br>
<br>

The DOM is a tree-like representation of the web page that gets loaded into the browser.
<br>
<br>
<div align="center">

![Image of Yaktocat](./pic_htmltree.gif)
</div>
<br>
It represents the web page using a‌‌ series of objects. The main object is the document object and after that, it consists of the elements used in the HTML in parent and child relationship.
<br>
<br>
Let's take an example, say that you want a button to change colors when it gets clicked or an image to slide when the mouse hovers over it. First, you need to reference those elements from your JavaScript.
<br>
<br>
<h2 align="center">How to select elements in DOM</h2>
There are 4 ways to select elements in DOM.

- getElementByID()
- getElementsByClassName()
- getElementsByTagName()
- CSS Selectors

### 1. getElementByID()

The most common way to access HTML element is to use the id of the element.

This example finds the element with id="intro":


    var myElement = document.getElementById("intro");

<br>

<br>

### 2. getElementsByClassName()

This method returns a collection of all elements in the document with the specified class name.

This example returns a list of all elements with class="intro".

    var x = document.getElementsByClassName("intro");

<br>

### 3. getElementsByTagName()

This method accepts a tag name and returns all the elements of the specified tag name in the order which they appear in the document.

This example finds all "p" elements:

    var x = document.getElementsByTagName("p");

<br>

### 4. CSS Selectors

This method is used to find all HTML elements that match a specified CSS selector (id, class names, types, attributes, values of attributes, etc).

This example returns a list of all "p" elements with class="intro".

    var x = document.querySelectorAll("p.intro");


