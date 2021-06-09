### Links
* Creating links between pages
* Linking to other sites
* Email links

Links are the defining feature of the web 
because they allow you to move from 
one web page to another — enabling the 
very idea of browsing or surfing.
You will commonly come across the following types of links:
● Links from one website to another
● Links from one page to another on the same website
● Links from one part of a web page to another part of the 
same page
● Links that open in a new browser window
● Links that start up your email program and address a new 
email to someone 
![links!](https://data-flair.training/blogs/wp-content/uploads/sites/2/2020/06/Links-in-HTML.jpg)

Links are created using the <a> element. Users can click on anything 
between the opening <a> tag and the closing </a> tag. You specify 
which page you want to link to using the href attribute.
Writing Links
<a href="http://www.imdb.com">IMDB</a>
This is the page the
link takes you to
Opening link tag
This is the text the
user clicks on
Closing
link tag

#### Linking to Other Sites
<a> 
Links are created using the <a> element which has an attribute  called href. The value of the href attribute is the page that you want people to go to when they click on the link.Users can click on anything that appears between the opening <a> tag and the closing </a> tag and will be taken to the page  specified in the href attribute.When you link to a different website, the value of the href attribute  will be the full web address for the site, which is  known as an absolute URL.

#### Linking to Other Pages on the Same Site 
<a>
When you are linking to other pages within the same site, you do not need to specify the domain name in the URL. You can use a shorthand known as a relative URL.If all the pages of the site are in the same folder, then the value of the  href attribute is just the name of the file.If you have different pages of a site in different folders, then you can use a slightly more complex syntax to indicate where the page is in relation to the current page. If you look at the download code for each chapter, you will see that the index.html file contains links that use relative URLs

### Functions, Methods, and Objects 
Objects in JavaScript are collections of key/value pairs. The values can consist of properties and methods, and may contain all other JavaScript data types, such as strings, numbers, and Booleans.

All objects in JavaScript descend from the parent Object constructor. Object has many useful built-in methods we can use and access to make working with individual objects straightforward. Unlike Array prototype methods like sort() and reverse() that are used on the array instance, Object methods are used directly on the Object constructor, and use the object instance as a parameter. This is known as a static method.

This tutorial will go over important built-in object methods, with each section below dealing with a specific method and providing an example of use.

Prerequisites
In order to get the most out of this tutorial, you should be familiar with creating, modifying, and working with objects, which you can review in the “Understanding Objects in JavaScript” article.

For additional guidance on JavaScript in general, you can review our How To Code in JavaScript series.

Object.create()
The Object.create() method is used to create a new object and link it to the prototype of an existing object.

We can create a job object instance, and extend it to a more specific object.

// Initialize an object with properties and methods
const job = {
    position: 'cashier',
    type: 'hourly',
    isAvailable: true,
    showDetails() {
        const accepting = this.isAvailable ? 'is accepting applications' : "is not currently accepting applications";

        console.log(`The ${this.position} position is ${this.type} and ${accepting}.`);
    }
};

// Use Object.create to pass properties
const barista = Object.create(job);

barista.position = "barista";
barista.showDetails();
 
Output
The barista position is hourly and is accepting applications.
The barista object now has one property — position — but all the other properties and methods from job are available through the prototype. Object.create() is useful for keeping code DRY by minimizing duplication.
