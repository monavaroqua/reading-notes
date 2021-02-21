# Understanding The Problem Domain Is The Hardest Part Of Programming
its hard because its like you can't see what you are trying to build, you don not have a picture of the problem domain.

problem domain should be clear and unambiguous to understand it

what can you do about it?

1 make problem domain easier

2 get better at understanding the problem domain

you can make problem domain easier by cutting down cases and foccus in a particular part

# what is an object?

Objects group together a set of variables and functions to create a model of a something to recognize. 

In an object : VARIABLES BECOME KNOWN AS PROPERTIES

IN AN OBJECT: FUNCTIONS BECOME KNOWN AS METHODS

Methods represent tasks that are associated with the object.

In JavaScript:

 Named functions have a name and value that is a set of statements to run if the function is called.

• Objects consist of a set of name/value pairs

create an object

literal notation : and its the easiest and most popular

var(name){
};

the object is the curly braces and their contents seperate each key with a new colume

seperate each property and method with a comma 

Accesing an object and dot notation :

you access the properties or method by using dot notation

you acess properties using square brackets

we use the name if the object followed by a period then the name of the property or method you want to access this is notation

the perios known sa the member operator and you can acees by using square bracket syntax

object name followed by square brackete and property name is inside them

# Document Object Model

The Document Object Model specifies how browsers should create a model of an HTML page and how JavaScript can access and update the 

contents of a web page while it is in the browser window.

ir covers two areas:

1- MAKING A MODEL OF THE HTML PAGE 

The DOM specifies the way in which the browser should structure this model using a DOM tree

2-ACCESSING AND CHANGING THE HTML PAGE


THE DOM TREE IS A MODEL OF A WEB PAGE

Every element, attribute, and piece of text in the HTML is represented by its own DOM node. At the top of the tree a document node is added

HTML elements describe the structure of an HTML page

ATTRIBUTE NODES

The opening tags of HTML elements can carry attributes and these are represented by attribute nodes in the DOM tree

Accessing and updating the DOM tree involves two steps:

1: Locate the node that represents the element you want to work with.

2: Use its text content, child elements, and attributes. 

methods that find elements in th DOM tree are called Dom queries.
aceesing elements:

DOM queries may return one element, or they may return a Nodelist, which is a collection of nodes.

