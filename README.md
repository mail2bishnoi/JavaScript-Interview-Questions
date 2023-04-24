## JavaScript Interview Questions

Q1. What is difference between undefined and null?

Ans. **Undefined:** Before any value is assigned to a variable it contains undefined. For example:

    let a;
    console.log(a); // undefined
    console.log(typeof a); // undefined
From above code segment its clear that undefined is also a data type in JavaScript. 

**Null:** When you want to make a variable or an object empty you can assign a null value to that variable. **Null** represents nothing. Some important points about you need to remember about null 

 - Null is primitive data type.
 - When you `console.log(typeof null) // object` its a bug in JavaScript from the early time and its there for some backward compatibility.
 - `console.log(null == undefined); // true` Because null and undefined both represent nothing.
 - `console.log(null === undefined); // false` Because their data type is different.
