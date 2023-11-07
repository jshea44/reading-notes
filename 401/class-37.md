# Redux - Combined Reducers

## Multiple Reducers Example

> 1. "Creating multiple reducers in Redux allows you to manage different parts of your application's state separately, improving modularity and maintainability."
> 2. You combine multiple reducers using Redux's `combineReducers` function.
> 3. "Managing state as an immutable object in Redux ensures predictability, simplifies debugging, and enables efficient change detection through shallow equality checks, improving performance and reliability."

## Redux Docs: Using Combined Reducers

> 1. `combineReducers` is a utility function to simplify the most common use case when writing REDUX REDUCERS.
> 2. "`combineReducers` assembles the new state tree by calling each slice reducer with its current state slice and the action, allowing each slice reducer to update its part of the state."
> 3. Initial state is used as a default value.

## Redux Docs: Combined Reducer Syntax

> 1. To manage independent parts of the state and improve code organization.
> 2. The `combineReducers` helper function turns an object with different reducing functions into a single reducing function you can pass to `createStore`.
> 3. A popular convention when naming reducers is to name them after the state slices they manage.

## Things I want to know more about

## Resources

- ChatGPT
