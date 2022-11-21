# Redux 

## Reducers and Actions

Reducers are  pure JS functions which take in the previous state and an action and return the newly updated state. Reducers do not change any part of the state. Rather a reducer produces a new instance of the state with all the necessary updates.

There can either be one reducer if it is a simple app or multiple reducers taking care of different parts or slices of the global state in a bigger application.

For example, there can be a reducer handling the state of the cart in a shopping application, then there can be a reducer handling the user details part of the application, and so on. They can only make copies of the original values, and then they can mutate the copies.

Actions are the only source of information for the store as per Redux official documentation. It carries a payload of information from your application to store.

## Redux Toolkit

The Redux Toolkit package is intended to be the standard way to write Redux logic. It was originally created to help you:

Configure a Redux store is too complicated.
To have what you need in one place.
To reduce code.

Redux Toolkit also includes a powerful data fetching and caching capability.

To install:

```
npm install @reduxjs/toolkit

```

## createSlice

createSlice is function that accepts an initial state, an object of reducer functions, and a "slice name", and automatically generates action creators and action types that correspond to the reducers and state.

```
import { createSlice } from '@reduxjs/toolkit'

const initialState = { value: 0 }

const counterSlice = createSlice({
  name: 'counter',
  initialState,
  reducers: {
    increment(state) {
      state.value++
    },
    decrement(state) {
      state.value--
    },
    incrementByAmount(state, action) {
      state.value += action.payload
    },
  },
})

export const { increment, decrement, incrementByAmount } = counterSlice.actions
export default counterSlice.reducer
```
createSlice accepts a single configuration object parameter as shown below

```
function createSlice({
    name: string,
    initialState: any,
    reducers: Object<string, ReducerFunction | ReducerAndPrepareObject>
    extraReducers?:
    | Object<string, ReducerFunction>
    | ((builder: ActionReducerMapBuilder<State>) => void)
})
```
