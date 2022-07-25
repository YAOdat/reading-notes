What does .map() return?
a new arry.
If I want to loop through an array and display each value in JSX, how do I do that in React?
using the JavaScript map() function.  We return a <li> element for each item.
Each list item needs a unique ____.
  Key
What is the purpose of a key?
  to produce two different arrays
  
  
  _________________
  
  What is the spread operator?
  
    Spread operator allows us to quickly copy all or part of an existing array or object into another array or object.
  
List 4 things that the spread operator can do.
  
Copying an array
Concatenating or combining arrays
Using Math functions
Using an array as arguments
  
Give an example of using the spread operator to combine two arrays.
  
 const fruits = ['🍏','🍊','🍌','🍉','🍍']
const moreFruits = [...fruits];
console.log(moreFruits) // Array(5) [ "🍏", "🍊", "🍌", "🍉", "🍍" ]
fruits[0] = '🍑'
console.log(...[...fruits,'...',...moreFruits]) //  🍑 🍊 🍌 🍉 🍍 ... 🍏 🍊 🍌 🍉 🍍
  
Give an example of using the spread operator to add a new item to an array.
  const fruits = ['🍏','🍊','🍌','🍉','🍍']
const moreFruits = [...fruits];
console.log(moreFruits) // Array(5) [ "🍏", "🍊", "🍌", "🍉", "🍍" ]
fruits[0] = '🍑'
console.log(...[...fruits,'...',...moreFruits]) //  🍑 🍊 🍌 🍉 🍍 ... 🍏 🍊 🍌 🍉 🍍
  
Give an example of using the spread operator to combine two objects into one.
  
  
  let person = {
    firstName: 'John',
    lastName: 'Doe',
    age: 25,
    ssn: '123-456-2356'
};


let job = {
    jobTitle: 'JavaScript Developer',
    location: 'USA'
};

let employee = {
    ...person,
    ...job
};

console.log(employee);

  
___________________________
  
  
 In the video, what is the first step that the developer does to pass functions between components?
In your own words, what does the increment function do?
How can you pass a method from a parent component into a child component?
How does the child component invoke a method that was passed to it from a parent component?
