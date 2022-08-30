Readings: Chart.js, Canvas
Below you will find some reading material, code samples, and some additional resources that support the topic for this class and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

Reading
JavaScript Canvas

1. What does the <canvas> allow a developer to acheive? HTML5 features the <canvas> element that allows you to draw 2D graphics using JavaScript.

The <canvas> element requires at least two attributes: width and height that specify the size of the canvas:

<canvas width="500" height="300" id="canvas"></canvas>
Canvas generates an access code that is later exchanged for an API token by the external application. 

2. What is the importance of the closing `</canvas> tag?
The reason that canvas tag requires a separate closing tag is because it's actually possible to put content inside that will display instead of the canvas if the user's browser does not support HTML5.

3. Explain what the getContext() method does.
Chart.js Documentation:
getContext() method returns a drawing context on the canvas, or null if the context identifier is not supported, or the canvas has already been set to a different context mode.


4. What is Chart.js and how it can be brought into your project?
 Chart.js, a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page. It’s a well documented plugin that makes using all kinds of charts easy.

5. List 3 different Chart types you can create using Chart.js.
bar charts, line charts, pie charts


Easily Create Stunning Animated Charts with Chart.js

6. What are some advantages to displaying data via a chart over a table?
It allows you to summarize a large dataset in visual form; easily compare two or three data sets; better clarify trends than do tables; estimate key values at a glance.

7. How could Chart.js aid your previously created applications visually?
It can be used in the Salmon Cookie Application to display the data in charts.
