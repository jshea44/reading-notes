# Redux - Asynchronous Actions

## async actions

> 1. A redux store does not read things with asynchronicity, so it needs middleware to make this happen.
> 2. state shows on UI, event handler is dispatched to the middleware, middleware calls API, you get a response from the API back to middleware, another dispatch happens to the reducer, which updates state.
> 3. We are accommondating async in our Redux app by using thunk middleware.

## thunk middleware

> 1. You may need to use thunk middleware if you are using an async function, like making an API call.
> 2. Redux Thunk middleware allows you to write action creators that return a FUNCTION instead of an action.
> 3. "The inner thunk function's return value is made available through the dispatch function when it's invoked within the outer function."

## Things I want to know more about

## Resources

- ChatGPT
