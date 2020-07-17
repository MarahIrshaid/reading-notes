# Chapter 16: “Images” (pp.406-427):

In the CSS, you add selectors for
each of the class names, then
use the CSS width and height
properties to control the image
dimensions.


Centering images
Using CSS :
```img.align-center { display: block; margin: 0px auto;}```

background-image:
```p { background-image: url("images/pattern.gif");}```


You can specify the dimensions o XX f images using CSS.
This is very helpful when you use the same sized
images on several pages of your site.
XX Images can be aligned both horizontally and vertically
using CSS.
XX You can use a background image behind the box
created by any element on a page.
XX Background images can appear just once or be
repeated across the background of the box.
XX You can create image rollover effects by moving the
background position of an image.
XX To reduce the number of images your browser has to
load, you can create image sprites.


# Chapter 19: “Practical Information” (476-492):

**Search Engine Optimization (SEO ):**

Search engine optimization (or
SEO) is the practice of trying
to help your site appear nearer
the top of search engine results
when people look for the topics
that your website covers.

On-Page Techniques
On-page techniques are the
methods you can use on your
web pages to improve their
rating in search engines.

Off-Page Techniques
Getting other sites to link to you
is just as important as on-page
techniques. Search engines help
determine how to rank your
site by looking at the number of


**On-page SEO**


In every page of your website there are seven key places where keywords
(the words people might search on to find your site) can appear in order
to improve its findability.


1: Page Title
2: URL / Web Address
3: Headings
4: Text
5: Link Text
6: Image Alt Text
7: Page Descriptions

Search engine optimization h XX elps visitors find your
sites when using search engines.
XX Analytics tools such as Google Analytics allow you to
see how many people visit your site, how they find it,
and what they do when they get there.
XX To put your site on the web, you will need to obtain a
domain name and web hosting.
XX FTP programs allow you to transfer files from your
local computer to your web server.
XX Many companies provide platforms for blogging, email
newsletters, e-commerce and other popular website
tools (to save you writing them from scratch).



# This MDN article on audio and video elements:

Part of the HTML5 spec, the HTMLMediaElement API provides features to allow you to control video and audio players programmatically — for example HTMLMediaElement.play(), HTMLMediaElement.pause(), etc. This interface is available to both ```<audio>``` and ```<video>``` elements, as the features you'll want to implement are nearly identical. Let's go through an example, adding features as we go.



The whole player is wrapped in a ```<div>``` element, so it can all be styled as one unit if needed.
The ```<video>``` element contains two ```<source>``` elements so that different formats can be loaded depending on the browser viewing the site.
The controls HTML is probably the most interesting:
We have four ```<button>```s — play/pause, stop, rewind, and fast forward.
Each ```<button>``` has a class name, a data-icon attribute for defining what icon should be shown on each button (we'll show how this works in the below section), and an aria-label attribute to provide an understandable description of each button, since we're not providing a human-readable label inside the tags. The contents of aria-label attributes are read out by screenreaders when their users focus on the elements that contain them.
There is also a timer ```<div>```, which will report the elapsed time when the video is playing. Just for fun, we are providing two reporting mechanisms — a ```<span>``` containing the elapsed time in minutes and seconds, and an extra ```<div>``` that we will use to create a horizontal indicator bar that gets longer as the time elapses.




# Chapter 9: pages 201-206:


Whether you are creating an
animation or a media player in
Flash, the files you put on your
website are referred to as Flash
movies.
If you want to create your
own Flash movie, you need to
purchase the Flash authoring
environment from Adobe.

When you create a Flash file in
the Flash authoring environment,
it is saved with the .fla file
extension. In order to use this file
on a web page it has to be saved
in a different format known
as SWF. (It has the .swf file
extension.)

Since 2005, a number of factors have meant
that fewer websites are written in Flash or even
use elements of Flash in their pages. 



HTML5 replaced flash!
