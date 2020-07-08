# Chapter 5: “Images” (pp.94-125):

A picture can say a thousand words, and great
images help make the difference between an
average-looking site and a really engaging one.

A picture can say a thousand words, and great
images help make the difference between an
average-looking site and a really engaging one.


image tag:
```<img src="images/quokka.jpg" alt="A family of```
```quokka" title="The quokka is an Australian```
```marsupial that is similar in size to the```
```domestic cat." />```


The text used in the alt attribute
is often referred to as alt text.
It should give an accurate
description of the image content
so it can be understood by
screen reader software (used by
people with visual impairments)
and search engines.


Images often come with
captions. HTML5 has introduced
a new ```<figure>``` element to
contain images and their caption
so that the two are associated.
You can have more than one
image inside the ```<figure>```
element as long as they all share
the same caption.




# Chapter 11: “Color” (pp.246-263):


you can specify colors in CSS !!



 You can specify any
color in CSS in one of three ways:


1. rgb values

These express colors in terms
of how much red, green and
blue are used to make it up. For
example: 
 rgb(100,100,90)


2. hex codes
These are six-digit codes that
represent the amount of red,
green and blue in a color,
preceded by a pound or hash #
sign. For example: #ee3e80


3. color names
There are 147 predefined color
names that are recognized
by browsers. For example:
DarkCyan


CSS 3: Opacity opacity, rgba


hsl, hsla : 
hue
This is expressed as an angle
(between 0 and 360 degrees).
saturation
This is expressed as a
percentage.
lightness
This is expressed as a
percentage with 0% being white,
50% being normal, and 100%
being black.


# Chapter 12: “Text” (pp.264-299):

you can specify the **style** of the **text** (Normal , *Italic* or *Oblique* ).
or weight : light , medium , **bold** or **Black**
or strech :Condensed ,Regular or Extended.
or font-type : sans serif ...etc
and of course , font-size!

or
**uppercase**
This causes the text to appear
uppercase.
**lowercase**
this causes the text to appear
lowercase.
**capitalize**
This causes the first letter of
each word to appear capitalized.

The text-decoration property
allows you to specify the
following values:
**none**
This removes any decoration
already applied to the text.
**underline**
This adds a line underneath the
text.
**overline**
This adds a line over the top of
the text.
**line-through**
This adds a line through words.
**blink**
This animates the text to make it
flash on and off (however this is
generally frowned upon, as it is
considered rather annoying).


**text-align**
 this allows you to align text to right ,left or center
 
 
 *justify*
This indicates that every line in
a paragraph, except the last line,
should be set to take up the full
width of the containing box.


**vertical-align**
baseline
sub
super
top
text-top
middle
bottom
text-bottom




**text-shadow:**
```text-shadow: 1px 1px 0px #000000;```


**styling links:**
When pseudo-classes are
used, they should appear in this
order: :link, :visited, :hover,
:focus, :active.



the end


