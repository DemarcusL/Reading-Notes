# FORMS #

HTML borrows the concept of a form to refer to different
elements that allow you to collect information from visitors to
your site.
Whether you are adding a simple search box to your website or
you need to create more complicated insurance applications,
HTML forms give you a set of elements to collect data from
your users.

In addition to enabling users to
search, forms also allow users
to perform other functions
online. You will see forms
when registering as a member
of a website, when shopping
online, and when signing up for
newsletters or mailing lists.

There are several types of form controls that
you can use to collect information from visitors
to your site.

ADDING TEXT:

Making Choices:

Submitting Forms: Uploading Files:

Password input

Like a single line text box but it
masks the characters entered.

Text input (single-line)
Used for a single line of text such
as email addresses and names.

Text area (multi-line)
For longer areas of text, such as
messages and comments.

Checkboxes
When a user can select and
unselect one or more options.

Radio buttons
For use when a user must select
one of a number of options.

Drop-down boxes
When a user must pick one of a
number of options from a list.

Image buttons
Similar to submit buttons but
they allow you to use an image.

Submit buttons
To submit data from your form
to another web page.

File upload
Allows users to upload files
(e.g. images) to a website.

There are several CSS properties that
were created to work with specific types
of HTML elements, such as _lists, tables,
and forms_.

## Events ##

W hen you browse the web, your browser registers different
types of events. It's the browser's way of saying, "Hey, this
just happened." Your script can then respond to these events. 

Events are said to trigger a function or script. When the click event
fires on the element in this diagram, it could trigger a script that enlarges
the selected item

When the user interacts with the HTML on a web page, there are three
steps involved in getting it to trigger some JavaScript code.
Together these steps are known as event handling. 

1
Select t he element
node(s) you want the
script to respond to.
For example, if you want to
trigger a function when a user
clicks on a specific link, you need
to get the DOM node for that
link element. 

2
Indicate which event on
the selected node(s) will
trigger the response.
Programmers call this binding an
event to a DOM node.
The previous two pages showed
a selection of the popular events
that you can monitor for. 

3
State the code you want
to run when the event
occurs.
W hen the event occurs, on a
specified element, it will trigger
a function. This may be a named
or an anonymous function. 

All modern browsers understand this way of creating an event handler,
but you can only attach one function to each event handler. 

Here is the syntax to bind an event to an element using an event handler,
and to indicate which function should execute when that event fires:
element .onevent functionName ;

### ELEMENT EVENT CODE ###

DOM element Event bound to node(s) Name of function to call (with
node to target preceded by word "on" no parentheses following it)