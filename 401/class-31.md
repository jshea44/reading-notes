# Context API

## Choosing the State Structure

Summarize the five principles for structuring state.

> 1. Group related state: " If you always update two or more state variables at the same time, consider merging them into a single state variable."
> 2. Avoid contradictoins in state: "When the state is structured in a way that several pieces of state may contradict and “disagree” with each other, you leave room for mistakes."
> 3. Avoid redundant state: "If you can calculate some information from the component’s props or its existing state variables during rendering, you should not put that information into that component’s state."
> 4. Avoid duplication state: "When the same data is duplicated between multiple state variables, or within nested objects, it is difficult to keep them in sync."
> 5. Avoid deeply nested state: "Deeply hierarchical state is not very convenient to update. When possible, prefer to structure state in a flat way."

## Passing State Deeply with Context

> 1. It aims to solve the problem of having a possible large project and instead of passing props all the way down the tree to specific components, those components can now 'reach up' to the Context Provider.
> 2. "Passing props or passing JSX as children to components should be attempted before using useContext."
> 3. The useReducer hook complements useContext for managing complex state in applications.

## Things I want to know more about

## Resources

- ChatGPT
- [Link](https://react.dev/learn/choosing-the-state-structure)
