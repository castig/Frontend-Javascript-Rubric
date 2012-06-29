#Frontend Web Development Assessment#

##Overview:##

The following is meant to be the seed of a community discussion around a baseline diagnostic for the discipline of Front-end Web Development. 

The test is meant for individuals seeking feedback on their self-learning and/or a stamp of baseline proficiency. There are two components of the assessment: 1) confirmation of fundamental concept understanding through standardized questions 2) assessment of practical ability to apply skill-set through development of a dynamic website project equivalent to a junior level portfolio piece in difficulty. This is then reviewed using a rubric to check for accomplishment of the following core learning objectives:

+ Clean, efficient, concise, logically structured, and easily readable code.
+ Consistency of HTML, CSS, and Javascript to given specification or mockup.
+ Responsiveness of site with an appropriate load-time (as measured by the YSlow plugin).
+ Organize site file structure in an intuitive manner, with separate files for HTML, CSS, and Javascript.
+ Use SEO techniques to optimize the site’s visibility in search engines.


##Project Rubric

**Criteria**

In evaluating project submissions each criteria item is evaluated using the following levels: 

3. High Proficiency 
2. Baseline Proficiency
1. Subpar or Lacking Proficiency 

***Functionality***

| Metric | High Proficiency |Baseline Proficiency |Subpar or Lacking Proficiency |
|--------|------------------|---------------------|------------------------------|
| Matching specifications |  The application functions exactly as intended. | The application functions mostly as intended. | The application does not function as intended.|
| Javascript Console Errors | No errors. | Less than [number] errors. | More than [number] errors. |
| Markup errors (missing/extra closing tags). | No errors. | Less than [number] errors. |  More than [number] errors. |
| CSS errors (non-existent properties, incorrect rule syntax). | No errors. | Less than [number] errors.|  More than [number] errors. |
| File references (images, css files, linked scripts). | No broken references. | Less than [number] broken references.| More than [number] broken references. |

***Appearance***

| Metric | High Proficiency |Baseline Proficiency |Subpar or Lacking Proficiency |
|--------|------------------|---------------------|------------------------------|
| Matching specifications | The application’s front-end matches the designs exactly. |The application’s front-end matches the designs closely, but not exactly. | Less than 50% of the application’s front-end matches the design. | 
| Visual errors (unnecessary vertical/horizontal scroll distances,misplaced content) | No visual errors. | Less than [number] errors. | More than [number] errors. |

***Performance***

| Metric | High Proficiency |Baseline Proficiency |Subpar or Lacking Proficiency |
|--------|------------------|---------------------|------------------------------|
| Responsiveness | The application feels light and fast. |The application is fast enough to keep a user from wanting to leave the page. | The application is slow and clunky. |
| Load Time | Using YSlow, the site is a grade A or better. | Using YSlow, the site is a B or better.| Using YSlow, the site is a C or below |

***Structure/Organization***

| Metric | High Proficiency |Baseline Proficiency |Subpar or Lacking Proficiency |
|--------|------------------|---------------------|------------------------------|
| File Structure | Files are separated into folders by file type and/or purpose. Folder names and folder structure is intuitive. | Files are separated into folders by file type and/or purpose. Folder names and folder structure might require some explanation to another developer. | Files are not all separated into folders by file type and/or purpose. Folder names and folder structure are not intuitive enough for sharing. |
| Separation of Concerns | CSS rules and Javascript are separated from HTML. | ? | CSS rules and Javascript are included in the HTML. | 
| SEO Techniques | SEO techniques (\<meta\> tags and header tags - \<h1\>, \<h2\>, \<h3\>) are used to effectively provide useful information to search engines throughout the code. | Some SEO techniques (\<meta\> tags and header tags - \<h1\>, \<h2\>,\<h3\>) are used to effectively provide useful information to search engines. | SEO techniques (\<meta\> tags and header tags - \<h1\>, \<h2\>, \<h3\>) are not effectively to provide useful information to search engines. |


**Code Quality**

**(on a 1-3 scale, 3 being the best)**

****\

**HTML**

​1. Rate the quality of the student’s HTML structure. Are the pages
broken down into logical sections?

\

​2. Rate the quality of the student’s choice of HTML tags. How often did
the student choose the best (most semantic) element for the job? Are
nested tags correctly nested (does the nesting make sense? Can a \<div\>
be a direct descendent of a \<ul\>)?

\

​3. Rate the quality of the student’s use of classes and IDs. Does the
student use classes on elements with similar purposes and/or similar
styling? Are class and ID names intuitive, meaningful, and concise?

\

​4. How easy is it to read the student’s HTML code? Does the student
indent consistently, do they leave frequent comments?

\

​5. Rate the separation of content from presentation. Does the student
use HTML to achieve visual effects when CSS would be more appropriate?

\

**CSS**

​1. Rate the quality of the student’s CSS structure. Is the code
separated into logical sections?

\

​2. Rate the quality of the student’s use of CSS properties. Do they
demonstrate that they understand a wide variety of properties and
techniques? Do they accomplish their desired visual outcomes in
standard, accepted ways or are they misusing certain properties?

\

​3. Rate the readability of the student’s CSS. Is it commented and
well-indented with consistent spacing?

\

​4. How concise is the student’s CSS code? Does the student make clever
use of selectors to keep the number of duplicate rules low?

\

**Javascript**

​1. Rate the organization of the student’s Javascript. Are procedural
code and event handlers separated from functions?

\

​2. Rate the quality of the student’s program logic. Are they
effectively using loops, functions, and conditionals? Are there easier
ways they could have accomplished certain things?

\

​3. Rate the readability of the student’s code. Is code well-indented
and consistently spaced? Are complex pieces of logic appropriately
commented?

\

​4. Rate the efficiency of the student’s code. Are they performing
unnecessary operations or are there situations where they could see
gains by approaching things in a different way?

\

​5. Rate the maintainability of a student’s code. Is the code DRY (free
from repetition of blocks of identical or highly similar code), do
variables have intuitive names?

\

**Project-specific Requirements**

​1. Student included the jQuery library and included code to affect the
content and/or the behavior of their html pages using jQuery selectors
and functionality.

\

​2. Student’s project demonstrates understanding of the following
concepts:

Basic control flow statements of Javascript (if/else, loops, switches)

Data types (including functions and objects)

Logical operators (==, ===, !=, \<, \>, etc)

Using jQuery to traverse the DOM

Using jQuery to add/remove elements

\

​3. Student’s jQuery code includes a call to at least one function
written in Javascript that returns an object that they then display
elements from.

\

​4. Student’s project includes the jQuery UI library and at least one
widget from the project (accordion, date picker, etc).

\

​5. Student’s project should also has at least one custom animation
using \$.animate()
