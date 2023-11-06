# Application State with Redux

## Dan Abramov Redux Tutorials

What is the first principle of Redux?

> 1. The first prinicple is: there's a single source of truth.

What is a store and what do we use our reducers for within that store?

> 2. A store is a central location for all states in an application. Reducers are used to create change in state in relation to specified actions.

Name three Redux store methods given to use by createStore and describe their use.

> 3. Store methods: `getState()` - used to access state at a given time, `dispath()` - "This method is used to dispatch actions to the Redux store. Actions are objects that describe what should change in the state. Dispatching an action triggers the state to be updated based on the reducers.", and `subscribe()` - allows you to register a listener function that will be called whenever the state in the Redux store changes.

Explain to a non-technical recruiter what `combineReducers()` does and why it is useful.

> 4. `combineReducers()` - "a Redux function that combines multiple reducer functions into a single reducer. It's useful for organizing and modularizing state management, making code more maintainable."

## Things I want to know more about

## Resources

- ChatGPT
