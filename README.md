# Description

In this lab, I had the opportunity to work on various tasks related to JavaScript coding and module exports. My main goal was to practice refactoring JavaScript code using modern syntax and explore different concepts. Here's a summary of what I did and the important things I learned:

First, I created a JavaScript file called "lab-03.js" in my cit281/p3 folder. I copied the provided code into this file, which included an object named "car" with its properties and some functions. The lab mentioned that I might not be able to complete the entire lab during the class, so I was prepared to work on the remaining parts on my own.

One of the tasks was to use object destructuring to declare two variables, "vin" and "year," and assign them the values from the "car" object. This allowed me to extract specific properties from the object in a more concise way.

Next, I worked on creating arrow functions to format and return car information. I followed the instructions to create different arrow function expressions: one with implicit return, one with explicit return, and another with object destructuring. These arrow functions provided a shorter syntax for writing functions and helped me understand the concept of implicit and explicit returns.

To further enhance my understanding of JavaScript syntax, I explored looping through objects and arrays. I used the "for..in" syntax to iterate through the properties of the "car" object and used the "hasOwnProperty()" method to ensure I only listed properties defined within the object. Additionally, I used the "for..of" syntax to iterate over the values in an array named "primes."

In order to create a modular code structure, I created a separate JavaScript module file called "lab-03-module.js." In this file, I added functions and updated the "module.exports" object to make the functions accessible for import using the "require()" function. Specifically, I implemented the "reverseString" function using the spread operator and exported it from the module.

Returning to the "lab-03.js" file, I used the "require()" function to import the "reverseString" and "concatenateString" functions from the "lab-03-module.js" module. This allowed me to use these functions in my code.

Finally, I used the spread operator to manipulate strings. In one of the tasks, I wrote a single line of code that used the console.log(), reverseString(), and concatenateString() methods to output the string "cbacba."

Throughout the lab, I learned important concepts and techniques in JavaScript development. Object destructuring helped me extract specific properties from objects easily, and arrow functions provided a more concise syntax for creating functions. I also gained a deeper understanding of looping through objects and arrays using the "for..in" and "for..of" syntaxes. Additionally, I learned about modular code structure and how to export and import functions between files using the "module.exports" and "require()" mechanisms. The usage of the spread operator was particularly valuable in manipulating strings.

Overall, this lab provided me with practical hands-on experience in JavaScript refactoring, arrow functions, object and array manipulation, modular code organization, and the spread operator. These skills will undoubtedly contribute to my growth as a JavaScript developer, enabling me to write more efficient and readable code.
