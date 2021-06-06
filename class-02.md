### in this file we will discusse three main subject's :
1. text/html 
2. some css features 
3. introduction to java script

**From the Duckett HTML book**

![Duckett HTML book!](https://www.picclickimg.com/d/l400/pict/113913716769_/HTML-CSS-JAVASCRIPT-JQUERY-Web.jpg)

first let me  Briefly give you aSummary about  what is **HTML:** 
* HTML pages are text documents.
*  HTML uses tags (characters that sit inside angled
brackets) to give the information they surround special
meaning.
* Tags are often referred to as elements.
* Tags usually come in pairs. The opening tag denotes
the start of a piece of content; the closing tag denotes
the end.
*  Opening tags can carry attributes, which tell us more
about the content of that element.
*  Attributes require a name and a value.
* To learn HTML you need to know what tags are
available for you to use, what they do, and where they
can go.

here is the most important tags that will be used in html :
* ### Headings
<h1>
<h2>
<h3>
<h4>
<h5>
<h6>
* ### Paragraphs : 
 opening <p>
tag and closing </p> tag.
* ### Superscript & Subscrip
<sup> /<sub> 
* ### Line Breaks & Horizontal Rules
<br /> /<hr />
* ### Citations & Definitions
<cite>   /   <dfn>
 

## Summary TEXT : 
* HTML elements are used to describe the structure of
the page (e.g. headings, subheadings, paragraphs).
*  They also provide semantic information (e.g. where
emphasis should be placed, the definition of any
acronyms used, when given text is a quotation).

![html example !](https://www.advanced-ict.info/html/graphics/example2a.png)

### What is CSS for?
 CSS is a language for specifying how documents are presented to users — how they are styled, laid out, etc.

A document is usually a text file structured using a markup language — HTML is the most common markup language, but you may also come across other markup languages such as SVG or XML.

Presenting a document to a user means converting it into a form usable by your audience. Browsers, like Firefox, Chrome, or Edge , are designed to present documents visually, for example, on a computer screen, projector or printer.

**Note: A browser is sometimes called a user agent, which basically means a computer program that represents a person inside a computer system. Browsers are the main type of user agent we think of when talking about CSS, however, it is not the only one. There are other user agents available — such as those which convert HTML and CSS documents into PDFs to be printed.**

![what is css!](https://i0.wp.com/websitecreationworkshop.com/blog/wp-content/uploads/2019/09/css-v02-tny.png)


## How To Add CSS
When a browser reads a style sheet, it will format the HTML document according to the information in the style sheet.


### There are three ways of inserting a style sheet:

1. External CSS
2. Internal CSS
3. Inline CSS

#### **External CSS**
With an external style sheet, you can change the look of an entire website by changing just one file!

Each HTML page must include a reference to the external style sheet file inside the <link> element, inside the head section.

Example
External styles are defined within the <link> element, inside the <head> section of an HTML page:

<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="mystyle.css">
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
An external style sheet can be written in any text editor, and must be saved with a .css extension.

The external .css file should not contain any HTML tags.

Here is how the "mystyle.css" file looks:

"mystyle.css"
body {
  background-color: lightblue;
}

h1 {
  color: navy;
  margin-left: 20px;
}

### CSS color Property

**color** 	Specifies the text color. Look at CSS Color Values for a complete list of possible color values.	
initial	Sets this property to its default value. Read about initial	
inherit	Inherits this property from its parent element. Read about inherit	
More Examples
** Example**  
**Set the text color with a HEX value:**

**body {color: #92a8d1;} **

![CSS color Property!](https://www.wideskills.com/sites/default/files/subjects/HTML%20Tutorial/18/image1.png)


 ### CSS Tools: Reset CSS
 The goal of a reset stylesheet is to reduce browser inconsistencies in things like default line heights, margins and font sizes of headings, and so on. The general reasoning behind this was discussed in a May 2007 post, if you're interested. Reset styles quite often appear in CSS frameworks, and the original "meyerweb reset" found its way into Blueprint, among others.

The reset styles given here are intentionally very generic. There isn't any default color or background set for the body element, for example. I don't particularly recommend that you just use this in its unaltered state in your own projects. It should be tweaked, edited, extended, and otherwise tuned to match your specific reset baseline. Fill in your preferred colors for the page, links, and so on.


# Dynamic web pages with JavaScript

### JavaScript has the following types of operators. This section describes the operators and contains information about operator precedence.

* Assignment operators
* Comparison operators
* Arithmetic operators
* Bitwise operators
* Logical operators
* String operators
* Conditional (ternary) operator
* Comma operator
* Unary operators
* Relational operators

JavaScript has both binary and unary operators, and one special ternary operator, the conditional operator. A binary operator requires two operands, one before the operator and one after the operator:


