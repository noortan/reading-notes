### in this file we will continue read more about these subjects 

### Linking to a Specific Part of the Same Page

At the top of a long page you might want to add a list of contents that links to the corresponding sections lower down. Or you might want to add a link from part way down the page back to the top of it to save users from having to scroll back to the top.
Before you can link to a specific part of a page, you need to identify the points in the page that the link will go to. You do this using the id attribute (which can be used on every HTML element). You can see that the
<h1> and <h2> elements in this example have been given id attributes that identify those sections of the page.
The value of the id attribute should start with a letter or an underscore (not a number or any other character) and, on a single page, no two id attributes should have the same value.
To link to an element that uses an id attribute you use the  **<a>** element again, but the value of the href attribute starts with the # symbol, followed by the value of the id attribute of the element you want to link to. In this example, <a href="#top"> links to the <h1> element at the top of the page whose id attribute has a value of top.

For example, to link to the bottom of the homepage of the website that accompanies this book, you would write:
<a href="http:/www.htmlandcssbookcom/#bottom">

![Linking to a Specific Part of the Same Page!](https://i.ytimg.com/vi/Vg-fEVtmQVI/maxresdefault.jpg)

* Links are created using the <a> element.
* X The <a> element uses the href attribute to indicate
* the page you are linking to.
* X If you are linking to a page within your own site, it is
* best to use relative links rather than qualified URLs.
* X You can create links to open email programs with an
* email address in the "to" field.
* X You can use the id attribute to target elements within
* a page that can be linked to.

## Images

There are many reasons why you might want to add an image to a web page: you might want to include a logo,photograph, illustration, diagram, or chart.
There are several things to consider when selecting and preparing images for your site, but taking time to get them right will make it look more attractive and professionalو In this chapter you will learn how to:
*  Include an image in your web pages using HTML
*  Pick which image format to use
*  Show an image at the right size
*  Optimize an image for use on the web to make pages
load faster

### Adding Images
<img> To add an image into the page you need to use an <img> element. This is an empty element (which means there is no closing tag). It must carry the following two attributes: src This tells the browser where it can find the image file. This will usually be a relative URL pointing to an image on your own site. (Here you can see that the images are in a child folder called images — relative URLs were covered on pages 83-84). alt
This provides a text description of the image which describes the image if you cannot see it.+title You can also use the title attribute with the <img> element to provide additional information about the image. Most browsers will display the content of this attribute in a tootip when the user hovers over the image

* ###  Height & Width  of Images
You will also often see an <img> element use two other attributes that specify its size:
**height**
This specifies the height of the image in pixels.
**width**
This specifies the width of the image in pixels
GIF is also a lossless image format that uses LZW compression algorithm. It was favoured over PNG for simple graphics in websites in its early days because the support of PNG was still growing. Given that PNG is now supported across all major devices and that PNG compression is about 5–25% better than GIF compression, GIF images are now mainly used only if the image contains animations.
### Color
* How to specify colors
* Color terminology and contrast
* Background color

The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways:
1. rgb values //example: rgb(100,100,90)
2. hex codes //For example: #ee3e80
3. color names// For example:DarkCya

### Text”
**font-family** 
he font-family property allows you to specify the typeface that should be used for
any text inside the element(s) to which a CSS rule applies.
The value of this property is the name of the typeface you want to use.
The people who are visiting your site need the typeface you have specified installed on their computer in order for it to be displayed.
You can specify a list of fonts separated by commas so that, if the user does not have your first choice of typeface installed, the browser can try to use an alternative font from the list.


**font-size**
The font-size property enables you to specify a size for the font. There are several ways to specify the size of a font. The most common are:
1. pixels
2. percentages
3. ems

