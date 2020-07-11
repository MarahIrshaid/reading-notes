# Understanding the problem domain is the hardest part of programming:

Why problem domains are hard
Programming is easy if you understand the problem domain
What can you do about it?
If understanding the problem domain is the hardest part of programming and you want to make programming easier, you can do one of two things:

Make the problem domain easier
Get better at understanding the problem domain

# Chapter 3: “Object Literals” (pp.100-105):

IN AN OBJECT: FUNCTIONS BECOME
KNOWN AS METHODS
IN AN OBJECT: VARIABLES BECOME
KNOWN AS PROPERTIES

If you had two objects on the
same page, you would create
each one using the same
notation but store them in
variables with different names.

# Chapter 5: “Document Object Model” (pp.183-242):

![DOM](https://www.w3.org/TR/WD-DOM/table.gif)

ATTRIBUTE NODES
The opening tags of HTML elements can carry
attributes and these are represented by attribute
nodes in the DOM tree.


TEXT NODES
Once you have accessed an element node, you
can then reach the text within that element. This is
stored in its own text node.

DOM queries:
```getElementById('one');```



There are a couple of ways to do this:

Finding HTML elements by id
Finding HTML elements by tag name
Finding HTML elements by class name
Finding HTML elements by CSS selectors
Finding HTML elements by HTML object collections


The browser represents the page using a DOM tree.
DOM trees have four types of nodes: document nodes,
element nodes, attribute nodes, and text nodes.
You can select element nodes by their id or cl ass
attributes, by tag name, or using CSS selector syntax.
Whenever a DOM query can return more than one
node, it will always return a Nadel i st.
From an element node, you can access and update its
content using properties such as textContent and
i nnerHTML or using DOM manipulation techniques.
An element node can contain multiple text nodes and
child elements that are siblings of each other.
In older browsers, implementation of the DOM is
inconsistent (and is a popular reason for using jQuery).
Browsers offer tools for viewing the DOM tree .
