What is the single responsibility principle and how does it apply to components?
A technique that states that a component should ideally only do one thing.

What does it mean to build a ‘static’ version of your application?
An application in which data doesn't change over time, it requires a lot of typing and less thinking.

Once you have a static application, what do you need to add?
add props.

What are the three questions you can ask to determine if something is state?

Is it passed in from a parent via props? If so, it probably isn’t state.
Does it remain unchanged over time? If so, it probably isn’t state.
Can you compute it based on any other state or props in your component? If so, it isn’t state.

How can you identify where state needs to live?

For each piece of state in the application:

Identify every component that renders something based on that state.
Find a common owner component (a single component above all the components that need the state in the hierarchy).
Either the common owner or another component higher up in the hierarchy should own the state.
If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.
Let’s run through this strategy for our application:


_______________________________________________________________________________________________


What is a “higher-order function”?
Functions that operate on other functions, either by taking them as arguments or by returning them.

Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
 it returns a function that returns a comparison between numbers

Explain how either map or reduce operates, with regards to higher-order functions.
map builds up new arrays when running
reduce builds a value by repeatedly taking a single element from the array and combining it with the current value. When summing numbers, you’d start with the number zero and, for each element, add that to the sum.
