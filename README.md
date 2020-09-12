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

