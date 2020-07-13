# chapter 15: Layout:

Liquid layout designs
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

