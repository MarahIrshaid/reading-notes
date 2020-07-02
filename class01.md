# Introduction pages 2-11:


a website consists mainly of HTML for structure , CSS for styling and JavaScript for interaction.
***what are Browsers***
People access websites using software called a web browser.


*** what are Web Servers***
When you ask your browser for a web page, the request is sent across the Internet to a special computer known as a web server which hosts the website.

***Screen readers***
Screen readers are programs that read out the contents of a computer screen to a user. They are commonly used by people with visual impairments.

Nowadays we have HTML5 and CSS3.

#### how the internet works:

When you visit a website, the web server
hosting that site could be anywhere in the
world. In order for you to find the location of
the web server, your browser will first connect
to a Domain Name System (DNS) server.


#### How connection to the internet happens:

1. When you connect to the web,
you do so via an Internet Service
Provider (ISP). You type a
domain name or web address
into your browser to visit a site;
for example: google.com,
bbc.co.uk, microsoft.com.


2. Your computer contacts a
network of servers called
Domain Name System (DNS)
servers. These act like phone
books; they tell your computer
the IP address associated with
the requested domain name.
An IP address is a number
of up to 12 digits separated
by periods / full stops. Every
device connected to the web
has a unique IP address; it is
like the phone number for that
computer.


3. The unique number that the
DNS server returns to your
computer allows your browser
to contact the web server
that hosts the website you
requested. A web server is a
computer that is constantly
connected to the web, and is set
up especially to send web pages
to users.

4. The web server then sends the
page you requested back to your
web browser.

# HTML Chapter 1: “Structure” (pp.12-39)

HTML Describes the Structure of Pages.

HTML uses tags like "<h1>"

the most important tags are <html> and <body>
each has an importance and job.
some tags hass opening tag and closing tags , but some has only opening tag.
EX: <p> </p>

### <p lang="fr">Paragraphe en Français</p>
lang is an attribute name, fr is an attribute value. these are used for adding styling.
<title> is used for adding a name for the page.


 HTML pages are text documents.
 Tags are often referred to as elements.


# HTML Chapter 8: “Extra Markup” (p.176-199):

HTML5 is the newest version of HTML , XML is the oldest, in between there's many versions of HTML. all vary in features.

<!-- --> is for adding a comment

<!DOCTYPE html> is for HTML5
you can add ID and class attribute to give the element a unique styling, ID adds a very unique styling, class for multiple-use styling , in CSS code we use #id and .class ...

Some elements will always
appear to start on a new line in
the browser window. These are
known as block level elements. 

Examples of block elements are
<h1>, <p>, <ul>, and <li>.


Some elements will always
appear to continue on the
same line as their neighbouring
elements. These are known as
inline elements.
Examples of inline elements are
<a>, <b>, <em>, and <img>.




Grouping Text &
Elements In a Block ,use <div>


Grouping Text &
Elements Inline, use <span>




<iframe> chapter-08/iframes.html HTML
An iframe is like a little window
that has been cut into your
page — and in that window you
can see another page. The term
iframe is an abbreviation of inline
frame

Information About
Your Pages
<meta>


# HTML Chapter 17: “HTML5 Layout” (pp.428-451):

The <header> and <footer>
elements can be used for:
● The main header or footer
that appears at the top or
bottom of every page on the
site.
● A header or footer for an
individual <article> or
<section> within the page.

The <nav> element is used to
contain the major navigational
blocks on the site such as the
primary site navigation.


The <article> element acts as
a container for any section of a
page that could stand alone and
potentially be syndicated.

The <aside> element has two
purposes, depending on whether
it is inside an <article>
element or not.

When the <aside> element
is used inside an <article>
element, it should contain
information that is related to the
article but not essential to its
overall meaning


The <section> element groups
related content together, and
typically each section would
have its own heading.

The purpose of the <hgroup>
element is to group together a
set of one or more <h1> through
<h6> elements so that they are
treated as one single heading


# HTML Chapter 18: “Process & Design” (pp.452-475):
How Often People Will
Visit Your Site ?
you should think of all the reasons that hold anyone to visit your website and use that to design your website in a good manner.
 make a site map
 ![Alt Text](https://online.visual-paradigm.com/repository/images/4eca449a-3fba-43f1-bc43-817dcdde3d23.png)


 you should make a framework too.


 You can differentiate between pieces of information
using size, color, and style.
X You can use grouping and similarity to help simplify
the information you present.

# JS Chapter 1: “The ABC of Programming” (pp.11-52):

A script is a series of instructions that the computer
can follow in order to achieve a goal.
Each time the script runs, it might only use a subset of
all the instructions. 

#### what is Objects :

object is a case in computer language that has properities 
In computer programming, each physical thing in
the world can be represented as an object. There are
two different types of objects here: a hotel and a car.
Programmers might say that there is one instance of
the hotel object, and two instances of the car object. 

Each object can have its own:
• Properties
• Events
• Methods 
</br>
a property is information about the object
events are :Programmers choose which events they respond to.
When a specific event happens, that event can be
used to trigger a specific section of the code. 

WHAT DOES A METHOD DO?
The code for a method can contain lots of
instructions that together represent one task. 



WEB BROWSERS ARE
PROGRAMS BUILT
USING OBJECTS 

#### HOW A BROWSER SEES A WEB PAGE 
1. RECEIVE A PAGE AS
HTML CODE 
2. CREATE A MODEL OF
THE PAGE AND STORE
IT IN MEMORY 
3. USE A RENDERING
ENGINE TO SHOW THE
PAGE ON SCREEN 

The HTML <script> element is
used to load the JavaScript file
into the page. It has an attribute
called src, whose value is the
path to the script you created. 

#### document.write('something here')
 document : document object , represent the entire webpage. 
 write : method of the document ,object allows writing new things on the HTML page on where <script> tag lays.
.: member operator
something here : parameters , the new thing you want to write.



If you view the source code of the page in the browser,
the JavaScript will not have changed the HTML,
because the script works with the model of the web
page that the browser has created. 




