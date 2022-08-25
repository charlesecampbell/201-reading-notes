Charles E. Campbell
8/24/22
Readings: Forms and JS Events
Below you will find some reading material, code samples, and some additional resources that support the topic for this class and the upcoming lecture.

Reading
HTML Forms
Your first Web Form. How To Structure A Web Form.

1. Why are forms so important in web development?
Forms are important in web development for marking up HTML structure, styling form controls, validating form data, and submitting date to the server.

2. When designing a form, what are some key things to keep in mind when it comes to user experience?
Here are some things to keep in mind related to the user expericence. 
1. You should present Fields in a Single Column Layout.
2. You should minimize the Number of Input Fields and User Typing Effort.
3. You should match Fields to the Size of the Input.
4. You should Place Labels Above the Corresponding Input Felds.


3. List 5 form elements and explain their importance.
1. Text Box Input - Input tag is used to capture text such as a name, email, address, or any other type of text.
2. Check Box - A box that you can click and it can be checked or unchecked. When the check box is checked you are setting the check box to true. Otherwise if it is unchecked, it is false.
3. Radio Input - A radio select input allows a user a specific amount of options to select from. You can think of this like a multiple choice select. The user can only select one of the options.
4. File Input - A File input is used to allow users to upload images or files. 
5. Submit Button - A way to submit our form with all the data.
https://devdojo.com/guide/html/form-elements

Learn JS
Introduction To Events.

4. How would you describe events to a non-technical friend?
Google Website and Email are events that require input such as searching for information or sending an email to another person.

5. When using the addEventListener() method, what 2 arguments will you need to provide? 1. Event and 2. listener - The event to listen for, and a second argument to be called whenever the described event gets fired.
https://www.geeksforgeeks.org/javascript-addeventlistener-with-examples/

6. Describe the event object. 
The event object contains a number of properties that describe the event that occurred.

7. Why is the target within the event object useful?
The target property can be the element that registered for the event or a descendant of it. It is often useful to compare event.target to this in order to determine if the event is being handled due to event bubbling. This property is very useful in event delegation, when events bubble.
https://api.jquery.com/event.target/

8. What is the difference between event bubbling and event capturing?
Event capturing means propagation of event is done from ancestor elements to child element in the DOM while event bubbling means propagation is done from child element to ancestor elements in the DOM

Bookmark and Review
HTML5 Input Types

Event Reference and listings


Things I want to know more about:
