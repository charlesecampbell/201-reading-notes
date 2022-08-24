Readings: HTML Lists, Control Flow with JS, and the CSS Box Model
Below you will find some reading material, code samples, and some additional resources that support the topic for this class and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

Reading
Learn HTML
Ordered and Unordered lists.

1. When should you use an unordered list in your HTML document?
To customise the bullets, to do without bullets and to wrap list items horizontally or vertically for multicolumn lists.

2. How do you change the bullet style of unordered list items?
Use CSS property list-style-type style attribute. The style attribute specifies an inline style for a <ul> tag.

3. When should you use an ordered list vs an unorder list in your HTML document?
Use an Unordered list when you want to create a list of related items, in no particular order. Use an Ordered list when you want to create a list of related items, in a specific order.

4. Describe two ways you can change the numbers on list items provided by an ordered list?
Change the style of numbers to roman or words

Learn CSS
The Box Model.

5. Describe the CSS properties of margin and padding as characters in a story. 
Describe the CSS properties of margin and padding as characters in a story.

6. What is their role in a story titled: “The Box Model”?
The padding section of the CSS Box Model sits in the space between the HTML content and the border. As with much of the other items in the box mode, the padding can be altered through its related properties.

7. List and describe the four parts of an HTML elements box as referred to by the box model.
List and describe the four parts of an HTML elements box as referred to by the box model.
1. Content area
The content area, bounded by the content edge, contains the "real" content of the element, such as text, an image, or a video player. Its dimensions are the content width (or content-box width) and the content height (or content-box height). It often has a background color or background image.

If the box-sizing property is set to content-box (default) and if the element is a block element, the content area's size can be explicitly defined with the width, min-width, max-width, height, min-height, and max-height properties.

2. Padding area
The padding area, bounded by the padding edge, extends the content area to include the element's padding. Its dimensions are the padding-box width and the padding-box height.

The thickness of the padding is determined by the padding-top, padding-right, padding-bottom, padding-left, and shorthand padding properties.

3. Border area
The border area, bounded by the border edge, extends the padding area to include the element's borders. Its dimensions are the border-box width and the border-box height.

The thickness of the borders are determined by the border-width and shorthand border properties. If the box-sizing property is set to border-box, the border area's size can be explicitly defined with the width, min-width, max-width, height, min-height, and max-height properties. When there is a background (background-color or background-image) set on a box, it extends to the outer edge of the border (i.e. extends underneath the border in z-ordering). This default behavior can be altered with the background-clip CSS property.

4. Margin area
The margin area, bounded by the margin edge, extends the border area to include an empty area used to separate the element from its neighbors. Its dimensions are the margin-box width and the margin-box height.

The size of the margin area is determined by the margin-top, margin-right, margin-bottom, margin-left, and shorthand margin properties. When margin collapsing occurs, the margin area is not clearly defined since margins are shared between boxes.

Learn JS
Arrays. Operators and Expressions. Conditionals. Loops.

8. What data types can you store inside of an Array?
What data types can you store inside of an Array?

9. Is the people array a valid JavaScript array? Yes If so, how can I access the values stored?  document.getElementsByName('the name')

 const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];


10. List five shorthand operators for assignment in javascript and describe what they do.
Name	        Shorthand operator	  Meaning
1. Assignment	            x = f()	  x = f()
2. Addition assignment	  x += f()	x = x + f()
3. Subtraction assignment	x -= f()	x = x - f()
4. Multiplication         x *= f()	x = x * f()
5. Division assignment	  x /= f()	x = x / f()


11.  Read the code below and evaluate the last expression and explain what the result would be and why.

 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;
 falsey, can't mix string, boolean and number types


12. Describe a real world example of when a conditional statement should be used in a JavaScript program.
Converse of a Conditional Statement
The converse of a true conditional statement does not automatically produce another true statement. It might create a true statement, or it could create nonsense:

If a polygon is a square, then it is also a quadrilateral.
That statement is true. But the converse of that is nonsense:

If a polygon is a quadrilateral, then it is also a square.
We know it is untrue because plenty of quadrilaterals exist that are not squares.


13.  Give an example of when a Loop is useful in JavaScript.
Example 1: Display a Text Five Times
// program to display text 5 times
const n = 5;

// looping from i = 1 to 5
for (let i = 1; i <= n; i++) {
    console.log(`I love JavaScript.`);
}
Run Code
Output

I love JavaScript.
I love JavaScript.
I love JavaScript.
I love JavaScript.
I love JavaScript.