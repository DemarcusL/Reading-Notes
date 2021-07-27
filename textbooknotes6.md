# Tables #

There are several types of information that need to be displayed in a grid or table. For example: sports results, stock reports, train timetables.

When representing information in a table, you need to think in terms of a grid made up of rows and columns (a bit like a spreadsheet). In this chapter you will learn how to:
● Use the four key elements for creating tables
● Represent complex data using tables
● Add captions to tables

## Well what even is a table? ##

A table represents information in a grid format. Grids allow us to understand complex data by referencing information on two axes. Each block in the grid is referred to as a table cell. In HTML a table is written out row by row.

**_Well how do i set up a table?_**

<table>
The <table> element is used to create a table. The contents of the table are written out row
by row.
<tr>
You indicate the start of each row using the opening <tr> tag. (The tr stands for table row.) It is followed by one or more <td> elements (one for each cell in that row). At the end of the row you use a closing </tr> tag.
<td>
Each cell of a table is represented using a <td> element. (The td stands for table data.) At the end of each cell you use a closing </td> tag

Reference <a href="https://wtf.tw/ref/duckett.pdf"> Here (Page 139) </a> about table headings.

### Functions ###

*_What is a Function ?_*

Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of statements).

I am familiar with this topic.

#### Domain Modelling ####

Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.

Here's some tips to follow when building your own domain models.

1) When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
2) Model its attributes with a constructor function that defines and initializes properties.
3) Model its behaviors with small methods that focus on doing one job well.
4) Create instances using the new keyword followed by a call to a constructor function.
5) Store the newly created object in a variable so you can access its properties and methods from outside.
6) Use the this variable within methods so you can access the object's properties and methods from inside.

This tl;dr what taken from <a href="https://github.com/codefellows/domain_modeling#domain-modeling"> Here </a>. It encapsulates everything I read about perfectly.