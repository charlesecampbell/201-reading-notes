<head>Code 201 Reading Notes</head>
Compose a short poem describing how HTTP sends data between computers.
HTTP is an application protocol that defines a language for clients and servers to speak to each other.

Component Files are websites made up of many different files, which are like the different parts of the goods and you buy from shops for your mother.

Code Files are Websites built primarily from HTML, CSS and JavaScript, though your'll meet other technologies that you can pip.

Assets are a collective name for all the other stuff that makes up a website, such as images, music, video, Word documents and PDFs to fancy a user's delight.


Describe how HTML, CSS, and JS files are “parsed” in the browser.
The browser parses the HTML file first, and tje leads to the browser reorganizing any <link>-element referneces toexternal CSS stylsheets and any <script>-element referneces to scripts.
As the brower parses the HTML, it sends requests back to the server for any CSS files it has fround from <link> elemets, and from those, then parses the CSS amnd JavaScript.
The browser generates an in-memory DOM tree from tje parsed HTML, generates an in-memory CSSOM structure from the parsed CSS, and  compiles and executes the parsed JavaScript.
As the browser builds the DOM tree and applies the styles from the CSSOM tree and executes the JavaScript, a visual representation of the page is painted to the screen, and the user sees the page content and can begin to interact with it.


How can you find images to add to a Website?
Search the website or your computer for images to add to a website.


How do you create a String vs a Number in JavaScript?
Text Content must be enclosed in single or double quotationn marks.

What is a Variable and why are they important in JavaScript?
A Varable is something that may or does vary or change and is used to hold a value.


Introduction to HTML
What is an HTML attribute?
A Selector in a Style element that shows a name and value pair.

Describe the Anatomy of an HTMl element.
The opening tag: This consists of the name of the element (in this case, p), wrapped in opening and closing angle brackets. 

What is the Difference between <article> and <section> element tags?
Section Tag: When you just want to decorate any content in your page i.e. you want to add some functions then you can use section tag, also that can be replaced by the div tag. The section tag will be good when the content of any web page is appropriate for the contents outline and browsers does not give any attention to the outlines.
Article Tag: The article tag is a self-completed tag, this can be used for any of those reasons, where section tag is required plus the article tag place the content independently. Article tag can be used to place any social post, magazine article, blogs, list of related contents, any independent content.


Section Tag: When you just want to decorate any content in your page i.e. you want to add some functions then you can use section tag, also that can be replaced by the div tag. The section tag will be good when the content of any web page is appropriate for the contents outline and browsers does not give any attention to the outlines.
Article Tag: The article tag is a self-completed tag, this can be used for any of those reasons, where section tag is required plus the article tag place the content independently. Article tag can be used to place any social post, magazine article, blogs, list of related contents, any independent content.


How does metadata influence Search Engine Optimization?
Using metadata boosts your SEO efforts because it's written in the search engine's language. This helps search engines better understand the topic of your webpages and content. It also helps them display more relevant results to searchers.

How is the Meta HTML Tag used when specifying metadata?
The Meta Tag defines metadata about an HTML document. Metadata is data (information) about data. meta tags always go inside the head element, and are typically used to specify character set, page description, keywords, author of the document, and viewport settings.

Miscellaneous
The Meta Tag defines metadata about an HTML document. Metadata is data (information) about data. meta tags always go inside the head element, and are typically used to specify character set, page description, keywords, author of the document, and viewport settings.

What is the first step to designing a Website?
Goal identification to identify the purpose of the website.

What is the most important question to answer when designing a Website?
In the process of website development, the most important things is to create a clean, appealing design.


Why should you use an h1 element over a span element to display a top level heading?
In HTML, the h1 element is a semantic element, which gives the text it wraps around the top level heading on your page.

What are the benefits of using semantic tags in our HTML?
Some of the benefits from writing semantic markup are as follows:

Search engines will consider its contents as important keywords to influence the page's search rankings (see SEO)
Screen readers can use it as a signpost to help visually impaired users navigate a page
Finding blocks of meaningful code is significantly easier than searching through endless divs with or without semantic or namespaced classes
Suggests to the developer the type of data that will be populated
Semantic naming mirrors proper custom element/component naming


What is JavaScript?
JavaScript is a scripting or programming language that allows you to implement complex features on web pages — every time a web page does more than just sit there and display static information for you to look at — displaying timely content updates, interactive maps, animated 2D/3D graphics, scrolling video jukeboxes, etc. — you can bet that JavaScript is probably involved. It is the third layer of the layer cake of standard web technologies, two of which (HTML and CSS) we have covered in much more detail in other parts of the Learning Area.


Describe 2 things that require JavaScript in the Browser?
HTML and CSS


How can you add JavaScript to an HTML document?
You can add JavaScript code in an HTML document by employing the dedicated HTML tag script that wraps around JavaScript code. The script tag can be placed in the head section of your HTML or in the body section, depending on when you want the JavaScript to load.