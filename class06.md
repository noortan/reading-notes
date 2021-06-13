## Problem Domain, Objects, and the DOM
1. ### Problem Domain
Understanding The Problem Domain Is The Hardest Part Of Programming Why problem domains are hard??

because you can’t really see what you are trying to build very clearly.

What can you do about it?
* Make the problem domain easier
* Get better at understanding the problem domain
By creating a familiar problem domain, I found that both the tasks of me teaching a new technology and the viewer learning that technology were much easier, because it is very difficult to learn more than one thing at once.

![dom tree!](https://camo.githubusercontent.com/9494d67b617c9772da2c1ef1e41b169cf08a6026f76aa454518b8b1c057d2168/68747470733a2f2f736c696465706c617965722e636f6d2f736c6964652f31353039393532302f39312f696d616765732f352f526571756972656d656e74732b616e642b53706563696669636174696f6e2e6a7067)

2. ### Object Literals
Objects group together a set of variables and functions to create a modelof a something you would recognize from the real world. In an object,variables and functions take on new names.
* IN AN OBJECT: VARIABLES BECOME KNOWN AS PROPERTIES
* IN AN OBJECT: FUNCTIONS BECOME KNOWN AS METHODS




### DOM
The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.

The DOM is neither part of HTML, not part of JavaScript; it is a separate set of rules. It is implemented by all major browser makers, and covers two primary areas:

* MAKING A MODEL OF THE HTML PAGE
* ACCESSING AND CHANGING THE HTML PAGE
#### DOM TREE

![dom tree!](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/08/Js-Dom-Tree.png)

DOM tree have two sectio
1. ATTRIBUTE NODES : The opening tags of HTML elements can carry attributes and these are represented by attribute nodes in the DOM tree.

2. TEXT NODES : Once you have accessed an element node, you can then reach the text within that element. This is stored in its own text node.

WORKING WITH THE DOM TREE
Accessing and updating the DOM tree involves two steps:

Locate the node that represents the element you want to work with. Use its text content, child elements, and attributes.

STEP 1: ACCESS THE ELEMENTS

STEP 2: WORK WITH THOSE ELEMENTS

ACCESSING ELEMENTS
DOM queries may return one element, or they may return a Nodelist, which is a collection of nodes.

Accessing a DOM element By TagName:
1. getElementByTagName
2. getElementByTagName.html
3. getElementByClassName