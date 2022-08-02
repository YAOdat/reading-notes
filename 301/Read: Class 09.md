## Readings: FUNCTIONAL PROGRAMMING

**1. What is functional programming?**
is the process of building software by composing pure functions, avoiding shared state, mutable data, and side-effects. Functional programming is declarative rather than imperative, and application state flows through pure functions. Contrast with object oriented programming, where application state is usually shared and colocated with methods in objects.

**2. What is a pure function and how do we know if something is a pure function?**

A pure function is a function which is given the same input, will always return the same output and produces no side effects.

**3. What are the benefits of a pure function?**
They are immediately testable, and they always produce the same results if you pass in the same arguments.

**4. What is immutability?**
Immutable data cannot change its structure or the data in it. It's setting a value on a variable that cannot change, making that value a fact, or sort of like a source of truth — the same way a princess kisses a frog hoping it will turn into a handsome prince.

**5. What is Referential transparency?**
In functional programming, referential transparency is generally defined as the fact that an expression, in a program, may be replaced by its value (or anything having the same value) without changing the result of the program.


### [Node JS Tutorial for Beginners #6 - Modules and require()](https://www.youtube.com/watch?v=xHLd36QoS4k)

**1. What is a module?**
Module in Node. js is a simple or complex functionality organized in single or multiple JavaScript files which can be reused throughout the Node. js application. Each module in Node. js has its own context, so it cannot interfere with other modules or pollute global scope.

**2. What does the word ‘require’ do?**
to ask for authoritatively or imperatively; demand. to impose need or occasion for; make necessary or indispensable: The work required infinite patience. to call for or exact as obligatory; ordain: The law requires annual income-tax returns.

**3. How do we bring another module into the file the we are working in?**
'Require' imports the module, and enable us to use its functionality.

**4. What do we have to do to make a module available?**

Local/File-based modules: It defines the Node modules within a file in our application and is used within our application.

Core modules: The core modules are inbuilt modules in Node. js. 

Third-party modules: Third-party modules which are the external Node modules.
