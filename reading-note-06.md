https://canvas.instructure.com/courses/5047714/discussion_topics/15297586?module_item_id=69186344

Charles E. Campbell

Readings: Problem Domain, Objects, and the DOM
Below you will find some reading material, code samples, and some additional resources that support the topic for this class and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

Reading
JavaScript Object Basics

1. How would you describe an object to a non-technical friend you grew up with?
A digital things or components is a computer world that has properties and attributes like in the real world.

2. What are some advantages to creating object literals?
1. Object literal to create objects on the go with no intention of copying values to another object or maybe mapping one object to another.
2. To create multiple instances of a structure and perform operations based on predefined values, then you should use a function constructor.

3. How do objects differ from arrays?
Objects represent a special data type that is mutable and can be used to store a collection of data (rather than just a single value). Arrays are a special type of variable that is also mutable and can also be used to store a list of values.

4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
Bracket notation is another way to access a property of an object. To use bracket notation, write the name of the object, followed by brackets [] . Inside the brackets, write the property name as a string. Bracket notation, unlike dot notation, can be used with variables.


5. Evaluate the code below. What does the term this refer to and what is the advantage to using this?
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}
This is a function with a verable named dog that can not be changed. It represents a category named dog, with four properties of dog. The function return a string that calculates the human age of a dog named Spot.


Introduction To The DOM

6. What is the DOM?
The Document Object Model (DOM) is a programming interface for web documents. It represents the page so that programs can change the document.

7. Briefly describe the relationship between the DOM and JavaScript.
The DOM is not part of the JavaScript language, but is instead a Web API used to build websites.


Bookmark and Review
Understanding the problem domain is the hardest part of programming

8.  What’s the difference between primitive values and object references in JavaScript?
Primitive values are immutable — they cannot be changed after being created. Object references, however, are mutable and can be changed. 
