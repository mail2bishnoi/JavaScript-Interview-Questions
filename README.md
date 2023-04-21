# JavaScript-Interview-Questions

Q1. What is the difference between undefined and NULL?
Ans. Before any value is assigned to a variable it contains undefined.
For example

let x;

console.log(x); // undefined

console.log(typeof x); // undefined

From the above two outputs we can understand that in javascript undefined is also a datatype.

Null: When you have a variable or an object you want to make empty then you assign a null to a variable.
null represent nothing.

Some Tricks

console.log(null == undefined) // true --> because both represent nothing
console.log(null === undefined) // false --> because type of null and undefined is not same.
