# Reading: useState() Hook

## Thinking in React

> 1. Summarize the five steps of thinking in react.

    1. Break the UI into a component hierarchy - "Identify and name components in the mockup, applying programming principles, CSS selectors, and data model mapping. Organize components hierarchically."
    2. Build a static version in React - Build out the UI in the browser so you can see what it looks like. Don't add any interactivity yet, that includes state values.
    3. Find the minimal but complete representation of UI state - "For interactivity, establish minimal UI state. Keep it DRY (Don't Repeat Yourself). Identify state by its change, non-prop origin, and computability. In this app, search text and checkbox value are state."
    4. Identify where your state should live - "To manage state in React, determine which component should own each piece of state by identifying rendering components and their common parent. Place the state in the common parent or above it, or create a new component for it."
    5. Add inverse data flow - "To update state based on user input, enable data flow from form components to the top-level component by passing update functions down to SearchBar in React."

## State: A Component’s Memory

> 1. One reason is that when React re-renders, the local variable goes back to its original value, which in this case is 0. So the picture never changes.
> 2. The argument is the intital value. The two arguments are the getter and setter. In this case it's index and setIndex.
> 3. Component A can access Component B's state by passing it as props.

## Things I want to know more about

## Resources

- ChatGPT
