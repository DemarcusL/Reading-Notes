# Images #

You can control the size of an image using the width and height properties in CSS, just like you can for any other box.
Specifying image sizes helps pages to load more smoothly because the HTML and CSS code will often load before the
images, and telling the browser how much space to leave for an image allows it to render the rest of the page without waiting for the image to download.
You might think that your site is likely to have images of all different sizes, but a lot of sites use the same sized image across many of their pages. 

It is great practice to undersatnd the common size you want for certain images on your page so you can set those values with id's ahead of time and save you some effort.

Rather than using the <img>
element's align attribute, web
page authors are increasingly
using the float property to align
images. There are two ways that
this is commonly achieved:

1: The float property is added
to the class that was created to
represent the size of the image
(such as the example below).

img.align-left {
float: left;
margin-right: 10px;}
img.align-right {
float: right;
margin-left: 10px;}
img.medium {
width: 250px;
height: 250px;}

2: New classes are created with
names such as align-left or
align-right to align the images
to the left or right of the page.
These class names are used in
addition to classes that indicate
the size of the image.

You can see the
align-left and align-right
classes used to align the image.
It is also common to add a
margin to the image to ensure
that the text does not touch their
edges.

By default, images are inline elements. This means that they flow within the surrounding text.
In order to center an image, it should be turned into a blocklevel element using the display property with a value of block.
Once it has been made into a block-level element, there are two common ways in which you can horizontally center an image:

img.align-center {
display: block;
margin: 0px auto;}
img.medium {
width: 250px;
height: 250px;}

1: On the containing element,
you can use the text-align
property with a value of center.

2: On the image itself, you can
use the use the margin property
and set the values of the left and
right margins to auto.

You can also set certain elements to have background images for their specific boxes.

p {
background-img: url("...") ;
}

## Practical Knowledge ##

SEO - Search Engine Optimization

Search engine optimization (or
SEO) is the practice of trying
to help your site appear nearer
the top of search engine results
when people look for the topics
that your website covers.

At the heart of SEO is the idea of
working out which terms people
are likely to enter into a search
engine to find your site and then
using these terms in the right
places on your site to increase
the chances that search engines
will show a link to your site in
their results.

In order to determine who comes
first in the search results, search
engines do not only look at what
appears on your site. They also
consider how many sites link
to you (and how relevant those
links are). For this reason, SEO
is often split into two areas:
on-page techniques and off-page
techniques.

More To be added Soon ! Refer to textbook for more information !