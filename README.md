# [![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=F7E91F&width=435&lines=This+is+Data+Types+in+JavaScript)](https://git.io/typing-svg)

deploy:https://eight-data-types-js-maga.netlify.app/

![JS types Photo](https://github.com/AndyMagwayer/Vertical-Slider-JS/blob/main/JavaScript-data-types.svg)
Infinitely rotating vertical carousel animation. CSS only.

JavaScript has the primitive data types:

null
undefined
boolean
number
string
symbol – available from ES2015
bigint – available from ES2020
and a complex data type object.
JavaScript is a dynamically typed language. It means that a variable doesn’t associate with a type. In other words, a variable can hold a value of different types. For example:
let counter = 120; // counter is a number
counter = false;   // counter is now a boolean
counter = "foo";   // counter is now a string
To get the current type of the value that the variable stores, you use the typeof operator:
let counter = 120;
console.log(typeof(counter)); // "number"

counter = false; 
console.log(typeof(counter)); // "boolean"

counter = "Hi";
console.log(typeof(counter)); // "string"
Output:
let counter;
console.log(counter);        // undefined
console.log(typeof counter); // undefined
The undefined type
The undefined type is a primitive type that has only one value undefined. By default, when a variable is declared but not initialized, it is assigned the value of undefined.

Consider the following example:
