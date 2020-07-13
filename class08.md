# chapter 15: Layout:
**Normal flow**
Elements on webpages lay themselves out according to normal flow - until we do something to change that. This article explains the basics of normal flow as a grounding for learning how to change it.
**Flexbox**
Flexbox is a one-dimensional layout method for laying out items in rows or columns. Items flex to fill additional space and shrink to fit into smaller spaces. This article explains all the fundamentals. After studying this guide you can test your flexbox skills to check your understanding before moving on.
**Grids**
CSS Grid Layout is a two-dimensional layout system for the web. It lets you lay content out in rows and columns, and has many features that make building complex layouts straightforward. This article will give you all you need to know to get started with page layout, then test your grid skills before moving on.
**Floats**
Originally for floating images inside blocks of text, the float property became one of the most commonly used tools for creating multiple column layouts on webpages. With the advent of Flexbox and Grid it has now returned to its original purpose, as this article explains.
**Positioning**
Positioning allows you to take elements out of the normal document layout flow, and make them behave differently, for example sitting on top of one another, or always remaining in the same place inside the browser viewport. This article explains the different position values, and how to use them.
**Multiple-column layout**
The multiple-column layout specification gives you a method of laying content out in columns, as you might see in a newspaper. This article explains how to use this feature.
**Responsive design**
As more diverse screen sizes have appeared on web-enabled devices, the concept of responsive web design (RWD) has appeared: a set of practices that allows web pages to alter their layout and appearance to suit different screen widths, resolutions, etc. It is an idea that changed the way we design for a multi-device web, and in this article we'll help you understand the main techniques you need to know to master it.


**Liquid layout** designs
stretch and contract
as the user increases
or decreases the
size of their browser
window. They tend to
use percentages.

```<div>``` elements are often used as containing elements
to group together sections of a page.
XX Browsers display pages in normal flow unless you
specify relative, absolute, or fixed positioning.
XX The float property moves content to the left or right
of the page and can be used to create multi-column
layouts. (Floated items require a defined width.)
XX Pages can be fixed width or liquid (stretchy) layouts.
XX Designers keep pages within 960-1000 pixels wide,
and indicate what the site is about within the top 600
pixels (to demonstrate its relevance without scrolling).
XX Grids help create professional and flexible designs.
XX CSS Frameworks provide rules for common tasks.
XX You can include multiple CSS files in one page.



When you move any element from normal flow, boxes can overlap. The z-index property allows you to control which box appears on top. When the position property is given a value of absolute, the box is taken out of normal flow and no longer affects the position of other elements on the page.

position:fixed: It positions the element in relation to the browser window. Therefore, when a user scrolls down the page, it stays in the exact same place. It is a good idea to try this example in your browser to see the effect.

z-index When you use relative, fixed, or absolute positioning, boxes can overlap. If boxes do overlap, the elements that appear later in the HTML code sit on top of those that are earlier in the page.

Fixed Width Layouts Fixed width layout designs do not change size as the user increases or decreases the size of their browser window. Measurements tend to be given in pixels.

