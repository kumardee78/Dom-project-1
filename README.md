# Manipulating <div> Styles Using DOM

This repository contains code demonstrating how to dynamically change the style of a <div> element using JavaScript and the Document Object Model (DOM). Below are instructions on how to achieve this:

## Instructions
* Create the Directory: **DOM project-1**

* Navigate to the Directory: DOM project-1

* Create a HTML file: **index.html**

* Open the index.html file in your preferred code editor.

* Understand the Structure:

The HTML file contains a <div> element with an id of targetDiv. This is the element whose style we will be manipulating dynamically using JavaScript.

#### html code
<div id="wrapper"><!-- Content Goes Here --></div>

* Create script tag : it's just above closing tag of body. you will write JavaScript code how to manipulate the style of the <div> element. Manipulate the <div> Styles:



## Here's a breakdown of what you can do:

#### Change Color: 
Use style.color.
#### Change Background Color: 
Use style.backgroundColor.
#### Adjust Margin: 
Use style.margin.
#### Adjust Padding: 
Use style.padding.
#### Change Font Size: 
Use style.fontSize.
#### Change Font Weight: 
Use style.fontWeight.
#### Adjust Height: 
Use style.height.
#### Adjust Width: 
Use style.width. 

Modify the JavaScript code according to your requirements, and save the file.

#### Open the HTML File in a Browser:

Open the index.html file in a web browser. You should see the <div> element with its initial style.

#### Test the Changes:

Make changes to the JavaScript code in script.js file as per your requirements, and refresh the browser to see the updated styles applied to the <div> element.

#### Example
Here's an example of how you can change the background color of the <div> element:

#### javascript
// Get the <div> element by its ID

let divElement = document.getElementById("textDiv");

// Change the background color to red
divElement.style.backgroundColor = "red";
