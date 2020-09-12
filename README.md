# Document Object Model
### The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window. 
## THE DOM TREE IS A MODEL OF A WEB PAGE
### As a browser loads a web page, it creates a model of that page. The model is called a DOM tree, and it is stored in the browsers' memory. It consists of four main types of nodes:
* THE DOCUMENT NODE 
* ELEMENT NODES 
* ATTRIBUTE NODES
* TEXT NODES 
![DOM Tree](https://user-images.githubusercontent.com/70091044/93000953-1bb25d00-f534-11ea-91fc-0188fdd3c037.PNG)

## THE DOCUMENT NODE (yellow color)
### At the top of the tree a document node is added; it represents the entire page. When you access any element, attribute, or text node, you navigate to it via the document node. It is the starting point for all visits to the DOM tree. 

## ELEMENT NODES (green color)
### To access the DOM tree, you start by looking for elements. Once you find the element you want, then you can access its text and attribute nodes if you want to. This is why you start by learning methods that allow you to access element nodes, before learning to access and alter text or attributes. 

## ATTRIBUTE NODES
### The opening tags of HTML elements can carry attributes and these are represented by attribute nodes in the DOM tree.

## TEXT NODES
### Once you have accessed an element node, you can then reach the text within that element. This is stored in its own text node. 
## Caching DOM queries
### Methodw that find elements in the DOM tree are called *DOM queries*. When you need to work with an element more than once, you should use a variable to store the result of this query.
![DOM querie](https://user-images.githubusercontent.com/70091044/93001508-27078780-f538-11ea-96cb-a881aec89310.PNG)
## Methods that select individual elements
* getElementById(): is the quickest and most efficient way to access an ele,emt because no two elements van share the same value for their **id** attribute.

* querySelector(): is a more recent addition to the DOM, so it is not supported in older browsers. But it is very flexible because its parameter is a CSS selector, which means it can be used to accurately target many more elements.
![getElementById](https://user-images.githubusercontent.com/70091044/93001706-bc574b80-f539-11ea-86dc-3d2a00fd3160.PNG)

## SELECTING AN ELEMENT FROM A NODELIST 
### A Nodelist is a collection of element nodes. Each node is given an index number (a number that starts at zero, just like an array). 
### There are two ways to select an element from a Nodelist: The item() method and array syntax(variable name[] ). Both require the index number of the element you want. 
## Another methodes for selecting:
* SELECTI NG ELEMENTS USING CLASS ATTRIBUTES ( getElementByClassName() ) 
* SELECTING ELEMENTS BY TAG NAME (getElementByTagName() )
* SELECTING ELEMENTS USING CSS SELECTORS ( querySelector() ) (eturns the first element node that matches the CSS-style selector.) 
* querySe 1ectorA11 () returns a Nodelist of all of the matches. 
## Repeating actions for an entire nodelist
### When you have a NodeList, you can loop through each node in the collection and apply the same statements to each.
