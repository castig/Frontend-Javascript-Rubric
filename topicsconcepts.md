#[Frontend Web Development](readme.md)
##Core Topics and Concepts: 

The following is meant to be a structured listing of the core concepts that should be understood by an individual entering the field of web development. 

###HTML

1.1 Doctype - Understands how <!doctype html> compares to previous HTML/XHTML doctypes (ie. HTML5 is backwards compatible, and not a totally new language, rather it brings updates to previous versions of HTML)	
1.2 The <head> Element - Ability to place appropriate tags in the \<head> section of an HTML document: \<link>, \<script>, \<style>, \<meta> 

1.3  Meta Tags - Ability to use of meta tags and an understanding their limitations from an SEO (search engine optimization) perspective

1.4 The \<body> Element -  Ability to use core HTML tags in the <body> section of a web page: \<div>, \<p>, \<a>, \<br>, \<hr>, \<ul>, \<ol>, \<li>, \<table>, \<span>

1.5 - HTML5 Elements - Ability to properly use core HTML5 elements such as \<header>,\<footer>,\<nav>,\<aside>,\<section>

1.6 - Deprecated HTML tags - Avoids deprecated HTML tags (e.g. \<font>, \<center>, \<u>, etc.)  and opts for using more flexible alternatives with CSS

1.7 - Folder Structure - Develops and maintains appropriate folder structure: all site files and subfolders (images, css, js) should be contained in a semantically named parent folder. Furthermore, avoids using illegal characters (@, #, spacebar, etc.) when naming files and directories

1.8 Hyperlinks - Understands the various attributes of hyperlink tags for linking within and between pages, as well as using “mailto” and named anchors 

1.9 Identifying elements - Demonstrates comprehension of the difference between classes for identifying a type of element, and IDs for identifying a specific unique element on the page

1.10 Forms - Demonstrates ability to use the \<form> element and the basic attributes when creating text fields, text areas, hidden fields, single and multiple dropdown boxes, radio buttons, checkboxes and submit buttons 

1.11 Clean And Readable Code - Demonstrates ability to maintain clean and readable code including: consistent indentation, code commenting (e.g. when closing \<div> tags, demarcating sections of code, describing possibly ambiguous code choices)

1.12 Search Engine Optimization (SEO) - Understands SEO best-practices related to HTML markup, and content optimization 

###CSS

2.1 - Separation of Concerns - Understands HTML is primarily used for the organization and structure of web page content, while CSS is used for presentation style. Understands best practices such as including CSS in a separate file, and avoids using both embedded and inline CSS styles.  

2.2 CSS Syntax - Demonstrates ability to write a valid CSS statement 

2.3 Basic CSS Properties -  Demonstrates ability to use basic css properties such as: background, fonts & text, link selectors and link pseudo-classes 

2.4 Box Model - Understands the CSS Box Model, and demonstrates ability to properly manipulate elements using padding, margin, and border

2.5 Page Layout - Demonstrates ability to develop a web page using the following regions: header, footer, sidebar, and multi-column layouts.

2.6 Float - Demonstrates ability to use floats and clearing 

2.7 Position -  Demonstrates ability to use position: static, relative, absolute, fixed

2.8 Typography - Comprehension of the fundamental principles of web typography, and demonstrates ability of how to incorporate non-standard web typography into a project using the @font-face property

2.9 Grid Based Design - Understands the benefits of grid based design, and demonstrates ability to properly develop a web page using a grid system

2.10 Navigation - Demonstrates ability to manipulate a \<nav>\<ul>\<li>\<a> first-level navigation structure using HTML and CSS to arrange the elements both horizontally and vertically, as well an ability to style the elements such that they visually appear like buttons (ie. with a clickable padded region surrounding the elements and not just a hyperlink). 

2.11 Sprites - Understands the benefits of using image sprites, and demonstrates an ability to manipulate image sprites using the CSS property “background-position”

2.12 CSS3 Techniques - Understands the concept of CSS3 and demonstrates ability to develop using the following CSS3 techniques: border-radius, text-shadow, box-shadow, opacity, RGBA, vendor prefixes

2.13 Cascade - Demonstrates comprehension of the notion of CSS “cascade” including: importance, specificity and inheritance. 
	
2.14 Cross browser Issues - Understands the concept of cross browsers issues, rendering engines, and graceful degradation. Understands common tools and tricks for optimizing CSS across multiple browsers. 

###Web Development Process

3.1 HTTP Request - Understands the basics of an HTTP request including an understanding of the following: DNS, IP Address, web server, browser request 

3.2 The Web Development Process - Understands a typical web production workflow and the responsibilities designated to each of the various roles: user-experience (UX), internet architecture, and web design, front-end web developer, back-end web developer 

3.3 Web Design Fundamentals - Understands the difference between the various image file types (JPG, GIF, PNG), as well as basic web color principles: RBG, CMKY, hexadecimal color

3.3 Text Editors - Demonstrates ability to manage, create, edit, and delete files using a text editor. 

3.4 File Transfer Protocol (FTP) - Demonstrates ability to connect to a web server via a FTP client, manage files both locally and remotely, and update chmod file permissions. 

3.3 Web Inspector - Demonstrates ability to use the browser web inspector to view page source, manipulate DOM hierarchy and debug code. 

3.5 Version Control - Understands the importance of version control.

3.6 Git - Demonstrates ability to use git for version control, including but not limited to the following commands: init, clone, pull, add, commit, push and basic merge conflict resolution using a text editor manually.

###Javascript

4.1 Understand the classes of problems that javascript can be used to address

4.2 jQuery - knowing how to apply jquery to a project. Also understanding the basics of document ready and knowing how to create a local js file for your jQuery and to include it into the html page *after* the jquery library.

4.3 jQuery selectors - Familiarity with a range of different jQuery selectors for being able to access arbitrary elements within any given page.

4.4 jQuery functions - Use of jQuery functions to override the click function for a submit button or the behavior of a link on a page.

4.5 jQuery capabilities - Sense of the range of capabilities that jQuery provides and an understanding of how to pick arbitrary new features and use those to add functionality to a site.

4.6 Data types - Understanding the various javascript data types and also how automatic type coercion works (and doesn't work). 

4.7 Functions - Understanding of parameter passing and scope along with a sense of the difference between referencing a function and calling it using the function operator.

4.8 Objects - Understanding the basics of objects - a collection of key/value properties of any data type. Understanding the basics of constructor functions and the implications of the "this" scope for a function called within an object using method style function calling.

4.9 Prototypical inheritance - Understanding the basics of using prototypes to reuse elements of objects (both data and functions) and how to add behavior and properties to the prototype chain for any given object.

4.10 Debugging javascript - Understanding how to use alerts for very simple debugging and then how to write to and view console messages for non-trivial functionality.

4.11 jQuery UI - Understanding how jQuery UI fits into the jQuery world, and the ability to implement simple jQuery UI widgets like the accordion or date picker - including working with the themes to style the widgets appropriately.

4.11.1 Advanced forms - Understanding the common requirements for styling forms (warnings, information, default values in fields and error displays for invalid entries so they can work with back end developers (or write js) to create useful, usable modern forms.
(from HTML section) 

###AJAX

5.1  Why would you want to use AJAX? What are the most common classes of use cases for AJAX?

5.2 Basic AJAX - comfort with basic AJAX including the ability to modify the properties to customize an AJAX request.

5.3 API's - The ability to take any simple API and write some jQuery to call it and display the returned data (perhaps create a form that will create a custom AJAX request against a third party API and display the results).

5.4 GET vs POST - Understanding why you'd use each from a pragmatic perspective and perhaps a lightweight introduction to some of the basic principles of RESTful API design so the concepts aren't completely unfamiliar to the students.

5.5 Cross site scripting protection and jsonp. Understanding the implications and how to work with them.