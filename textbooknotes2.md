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