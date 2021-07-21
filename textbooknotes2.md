# Lists and Boxes #

## Lists

There are lots of occasions when we
need to use lists. HTML provides us with
three different types:
● Ordered lists are lists where each item in the list is
numbered. For example, the list might be a set of steps for
a recipe that must be performed in order, or a legal contract
where each point needs to be identified by a section
number.
● Unordered lists are lists that begin with a bullet point
(rather than characters that indicate order).
● Definition lists are made up of a set of terms along with the
definitions for each of those terms.

<ul>
The unordered list is created
with the <ul> element.
<li>
Each item in the list is placed
between an opening <li> tag
and a closing </li> tag. (The li
stands for list item.)
Browsers indent lists by default.
Sometimes you may see a type
attribute used with the <ul>
element to specify the type of
bullet point (circles, squares,
diamonds and so on). It is better
to use the CSS list-styletype property

<dl>
The definition list is created with
the <dl> element and usually
consists of a series of terms and
their definitions.
Inside the <dl> element you will
usually see pairs of <dt> and
<dd> elements.
<dt>
This is used to contain the term
being defined (the definition
term).
<dd>
This is used to contain the
definition.
Sometimes you might see a list
where there are two terms used
for the same definition or two
different definitions for the same
term.

## Boxes

You can set several properties that affect the appearance of
these boxes. In this chapter you will see how to:
● Control the dimensions of your boxes
● Create borders around boxes
● Set margins and padding for boxes
● Show and hide boxes

By default a box is sized just big
enough to hold its contents. To
set your own dimensions for a
box you can use the height and
width properties.
The most popular ways to
specify the size of a box are
to use pixels, percentages, or
ems. Traditionally, pixels have
been the most popular method
because they allow designers to
accurately control their size.
When you use percentages,
the size of the box is relative to
the size of the browser window
or, if the box is encased within
another box, it is a percentage of
the size of the containing box.
When you use ems, the size
of the box is based on the size
of text within it. Designers
have recently started to use
percentages and ems more for
measurements as they try to
create designs that are flexible
across devices which have
different-sized screens.

Some page designs expand and
shrink to fit the size of the user's
screen. In such designs, the
min-width property specifies
the smallest size a box can be
displayed at when the browser
window is narrow, and the
max-width property indicates
the maximum width a box can
stretch to when the browser
window is wide.
These are very helpful properties
to ensure that the content of
pages are legible (especially on
the smaller screens of handheld
devices). For example, you can
use the max-width property to
ensure that lines of text do not
appear too wide within a big
browser window and you can
use the min-width property
to make sure that they do not
appear too narrow.
You may find it helpful to try this
example out in your browser so
that you can see what happens
when you increase or decrease
the size of the browser window.

## JavaScript Basics

A script is a series of instructions that a computer can follow one-by-one.
Each individual instruction or step is known as a statement.
Statements should end with a semicolon. 

We will look at what the code on the right does
shortly, but for the moment note that:
• Each of the lines of code in green is a statement.
• The pink curly braces indicate the start and end
of a code block. (Each code block could contain
many more statements.)
• The code in purple determines which code
should run 

JavaScript is case sensitive so hourNow means
something different to HourNow or HOURNOW.
STATEMENTS ARE INSTRUCTIONS AND
EACH ONE STARTS ON A NEW LINE
A statement is an individual instruction that the
computer should follow. Each one should start on a
new line and end with a semicolon. This makes your
code easier to read and follow.
The semicolon also tells the JavaScript interpreter
when a step is over, indicating that it should move
to the next step.

var today= new Date{);
var hourNow = today.getHours{) ;
var greeting;
if (hourNow > 18) {
greeting= 'Good evening';
else if (hourNow > 12) {
greeting= 'Good afternoon';
else if (hourNow > O) {
greeting 'Good morning';
else {
greeting 'Welcome';
document.write(greeting) ; 

A script will have to temporarily
store the bits of information it
needs to do its job. It can store this
data in variables.
When you write JavaScript, you have to tell the
interpreter every individual step that you want it to
perform. This sometimes involves more detail than
you might expect.
Think about calculating the area of a wall; in math
the area of a rectangle is obtained by multiplying two
numbers:
width x height = area
You may be able to do calculations like this in
your head, bu t when writing a script to do this
calculation, you need to give the computer very
detailed instructions. You might tell it to perform the
following four steps in order:
1. Remember the value for width
2. Remember the value for height
3. Multiply width by height to get the area
4. Return the result to the user
In this case, you would use variables to "remember"
the values for width and height. (This also illustrates
how a scrip( contains very explicit instructions about
exactly what you want the computer to do.)
You can compare variables to short-term memory,
because once you leave the page, the browser will
forget any information it holds. 

