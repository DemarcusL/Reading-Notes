# HTML CSS Text Notes #

1) Structural markup: the elements that you can use to
describe both headings and paragraphs
● Semantic markup: which provides extra information; such
as where emphasis is placed in a sentence, that something
you have written is a quotation (and who said it), the
meaning of acronyms, and so on

2)By enclosing words in the tags
-b- and </b> we can make
characters appear bold.

3)In order to make code easier to
read, web page authors often
add extra spaces or start some
elements on new lines.
When the browser comes across
two or more spaces next to each
other, it only displays one space.
Similarly if it comes across a line
break, it treats that as a single
space too. This is known as
white space collapsing.

4)Visual editors often resemble
word processors. Although
each editor will differ slightly,
there are some features that
are common to most editors
that allow you to control the
presentation of text.
● Headings are created by
highlighting text then using
a drop-down box to select a
heading.
● Bold and italic text are
created by highlighting some
text and pressing a b or i
button.
● New paragraphs are created
using the return or the enter
key.
● Line breaks are created by
pressing the shift key and the
return key at the same time.
● Horizontal rules are created
using a button with a straight
line on it.
If you copy and paste text from
a program that allows you to
format text (such as Word) into
a visual editor, it may add extra
markup. To prevent this copy
the text into a plain text editor
first (such as Notepad on a PC
or TextEdit on a Mac) and then
copy it from that program and
paste it into the visual editor

## CSS ##

CSS allows you to create rules that specify how the content of
an element should appear. For example, you can specify that
the background of the page is cream, all paragraphs should
appear in gray using the Arial typeface, or that all level one
headings should be in a blue, italic, Times typeface.

CSS works by associating rules with HTML elements. These rules govern
how the content of specified elements should be displayed. A CSS rule
contains two parts: a selector and a declaration.

### link ###

The -link- element can be used
in an HTML document to tell the
browser where to find the CSS
file used to style the page. It is an
empty element (meaning it does
not need a closing tag), and it
lives inside the -head- element.
It should use three attributes:

### href ###

This specifies the path to the
CSS file (which is often placed in
a folder called css or styles).

### type ###

This attribute specifies the type
of document being linked to. The
value should be text/css.

### rel ###

This specifies the relationship
between the HTML page and
the file it is linked to. The value
should be stylesheet when
linking to a CSS file.
An HTML page can use more
than one CSS style sheet. To
do this it could have a -link-
element for every CSS file it
uses. For example, some authors
use one CSS file to control the
presentation (such as fonts and
colors) and a second to control
the layout.

## JavaScript ##

A script is a series of instructions that a computer can follow one-by-one.
Each individual instruction or step is known as a statement.
Statements should end with a semicolon.

You should write comments to explain what your code does.
They help make your code easier to read and understand.
This can help you and others who read your code.

var today= new Date();
var hour Now = today.getHours();
var greeting;
// Create a ne1~ dat e object
II Fi nd the current hour

A script will have to temporarily
store the bits of information it
needs to do its job. It can store this
data in variables.
When you write JavaScript, you have to tell the
interpreter every individual step that you want it to
perform. This sometimes involves more detail than
you might expect.
