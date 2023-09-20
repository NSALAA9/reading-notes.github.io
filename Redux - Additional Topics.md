
**1. What concerns are addressed by Redux Toolkit?**
   - Redux Toolkit addresses common concerns related to Redux, such as:
     - The complexity of configuring a Redux store.
     - The need to add multiple packages for Redux to be useful.
     - The amount of boilerplate code required in Redux applications.

**2. What does configureStore() do?**
   - `configureStore()` is a function provided by Redux Toolkit that simplifies the configuration of a Redux store. It offers simplified options and good defaults, automatically combines slice reducers, includes middleware like `redux-thunk` by default, and enables the use of the Redux DevTools Extension. Essentially, it streamlines the process of setting up a Redux store.

**3. How would I use createSlice()?**
   - `createSlice()` is a Redux Toolkit function used to define a slice of the Redux state. You would typically use it as follows:
     1. Define an initial state for your slice.
     2. Define reducers that specify how the state should be updated in response to actions.
     3. `createSlice()` will automatically generate action creators and action types based on your reducers.
     4. Export the generated action creators and reducer to use in your application.

**4. What is MobX?**
   - MobX is a library for managing the state of your application in a reactive and simplified way. It provides tools to make state management straightforward by automatically tracking dependencies and ensuring that everything that can be derived from the application state is derived automatically. MobX is often used with React to create reactive user interfaces.

**5. How does MobX make it “impossible” to produce an inconsistent state?**
   - MobX ensures that it is impossible to produce an inconsistent state by automatically tracking dependencies between data and computations (like derived values and reactions). When any part of the state changes, MobX updates all relevant derived values and reactions automatically, synchronously, and without glitches. This prevents inconsistencies in the state and ensures that the user interface remains in sync with the state.

**6. How would we build a reactive user interface?**
   - To build a reactive user interface using MobX and React:
     1. Define your application state as observable objects or arrays using MobX's `observable` function.
     2. Create computed values using MobX's `computed` decorator to automatically derive values from the state.
     3. Use the `observer` wrapper from the `mobx-react-lite` package to make React components reactive. This wrapper ensures that components re-render automatically when relevant data changes.
     4. Organize your components to reflect the structure of your observable state, and use them in your application to create a declarative and reactive UI.
     5. Changes to the observable state will trigger automatic updates in your UI components, eliminating the need for manual state management in your components.
