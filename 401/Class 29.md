# Redux
Redux is a predictable state container for JavaScript apps. It helps you write applications that behave consistently, run in different environments (client, server, and native), and are easy to test. In other words, it is a state management library.

## When to Use Redux

Redux is needed in applications where handling multiple states from multiple components efficiently can become challenging. Redux will basically store and manage all the application's states.

## Getting Started

To install Redux Toolkit, using NPM, use the following command:

```
npm install @reduxjs/toolkit

```
### Redux Store:

The Redux store is the main, central bucket which stores all the states of an application. It should be considered and maintained as a single source of truth for the state of the application.

In a React app, create a redux store, let us suppose that the app is all about a counter:

```
//app/store.js

import { configureStore } from '@reduxjs/toolkit'
import counterReducer from '../features/counter/counterSlice'

export default configureStore({
  reducer: {
    counter: counterReducer
  }
})

```
The Redux store is created using the configureStore function from Redux Toolkit. configureStore requires that we pass in a reducer argument. When we pass in an object like {counter: counterReducer}, that says that we want to have a state.counter section of our Redux state object, and that we want the counterReducer function to be in charge of deciding if and how to update the state.counter section whenever an action is dispatched.

### Actions in Redux

Actions are the only source of information for the store as per Redux official documentation. It carries a payload of information from your application to store. As discussed earlier, actions are plain JavaScript object that must have a type attribute to indicate the type of action performed.


### Redux Slice


Setting up a Redux Slice:

```
import { configureStore } from '@reduxjs/toolkit'
import usersReducer from '../features/users/usersSlice'
import postsReducer from '../features/posts/postsSlice'
import commentsReducer from '../features/comments/commentsSlice'

export default configureStore({
  reducer: {
    users: usersReducer,
    posts: postsReducer,
    comments: commentsReducer
  }
})
```
A slice is a collection of Redux reducer logic and actions for a feature in the React app.

## Summary 

The global state of an application is stored in an object tree within a single store.

The only way to change the state is to emit an action, which is an object describing what happened.

To specify the state tree transformation by actions, write pure reducers.
