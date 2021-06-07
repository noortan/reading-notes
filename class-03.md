### in these section we will contiune talking about HTML,JS let's first begain with HTML 
## lists
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

● Definition lists are made up of a set of terms along with the definitions for each of those terms.

![html list!](https://gocoding.org/wp-content/uploads/2020/06/Unordered-List-Example.png)
### Ordered lists
<ol>
The ordered list is created with
the <ol> element.
<li>
Each item in the list is placed
between an opening <li> tag
and a closing </li> tag. (The li
stands for list item.)

### Unordered lists 
<ul>
The unordered list is created
with the <ul> element.
<li>
Each item in the list is placed
between an opening <li> tag
and a closing </li> tag. (The li
stands for list item.)

### Definition lists
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
definition


## Boxes



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
different-sized screen

## JavaScript Switch Statement

![swithch statement!](https://www.udacity.com/blog/wp-content/uploads/2021/03/Screen-Shot-2021-03-22-at-4.31.51-PM.png)


The JavaScript Switch Statement
Use the switch statement to select one of many code blocks to be executed.

Syntax
switch(expression) {
  case x:
    // code block
    break;
  case y:
    // code block
    break;
  default:
    // code block
}
This is how it works:

* The switch expression is evaluated once.
* The value of the expression is compared with the values of each case.
* If there is a match, the associated block of code is executed.
* If there is no match, the default code block is executed.

### The break Keyword
When JavaScript reaches a break keyword, it breaks out of the switch block.

This will stop the execution inside the switch block.

It is not necessary to break the last case in a switch block. The block breaks (ends) there anyway.

**Note:** If you omit the break statement, the next case will be executed even if the evaluation does not match the case.

###  The default Keyword
The default keyword specifies the code to run if  there is no case match
