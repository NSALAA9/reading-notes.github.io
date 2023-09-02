# Context API

The five principles for structuring state in React components:

1. **Group Related State Variables:** Combine state variables that are consistently updated together into a single state variable. This keeps related data together, making it easier to manage.

2. **Avoid Contradictions in State:** Organize state to prevent conflicting or contradictory values. This ensures that the state remains consistent and avoids unexpected behaviors.

3. **Avoid Redundant State:** Do not store data in the component's state if it can be calculated or derived from props or existing state variables during rendering. This minimizes unnecessary data duplication.

4. **Avoid Duplication in State:** Prevent duplicating the same data across multiple state variables or nested objects. Duplication can lead to synchronization issues and bugs.

5. **Avoid Deeply Nested State:** Try to structure state in a flat manner rather than deeply nested objects. Deeply hierarchical state can be challenging to update and maintain, so keeping it flat simplifies state management.

These principles aim to make state management in React components more straightforward, reduce the risk of bugs, and improve code maintainability.
-------------------------------------------------
**1. What problem do Contexts aim to solve?**

Contexts in React aim to solve the problem of **prop drilling**. Prop drilling occurs when you have to pass data from a top-level component down through multiple levels of nested components just so that a deeply nested component can access that data. It can make the codebase harder to maintain and read, as you end up passing props through components that don't directly use that data.

**2. What is one technique to try before useContext?**

Before using `useContext`, a technique you can try is **prop drilling**. With prop drilling, you pass data as props from a parent component down to child components in the hierarchy. This is the default and straightforward way to share data in React. However, it can become cumbersome and less maintainable in large component trees or when many components need access to the same data.

**3. What hook complements useContext for complex applications?**

In complex applications where you're dealing with state management, the hook that complements `useContext` is **`useReducer`**. While `useContext` allows you to access shared data from a context provider, `useReducer` complements it by providing a way to manage complex state updates more effectively.

`useReducer` is often used with context when you need to share not just data but also functions or actions to modify that data across multiple components. It's particularly useful when you have a lot of components that depend on the same shared state or when state updates involve complex logic. Together, `useContext` and `useReducer` can help you create a powerful state management system in React.

