## Building Blocks of a React App:
- **Components:** Functional and class-based units that make up the UI.
- **JSX:** HTML-like syntax in JavaScript for defining UI structure.
- **Props:** Data passed from parent to child components.
- **State:** Dynamic data managed within a component.
- **Context:** Mechanism for sharing data across components.
- **Hooks:** Functions for state and lifecycle management.
- **Lifecycle Methods (class components):** Methods called during component lifecycle.

## Difference Between HTML Element and React Component:
- HTML elements define web page structure in the DOM.
- React components encapsulate UI logic and behavior.

## JSX and its Purpose:
- JSX allows HTML-like code in JavaScript.
- Enhances readability and composition of React UI components.

## Embedding JavaScript Expressions in JSX:
- Use curly braces `{}` to embed JS expressions in JSX.
- Example: `<p>Hello, {name}!</p>`.

## Special Features for Iteration and Conditional Logic:
- JSX supports iteration (using `map`) and conditional rendering.

## How React Responds to User Inputs:
- Components use state and events to handle user input.
- Event handlers modify state, triggering re-render.

## Word Indicating a React Component Manages Data with a Hook:
- "Hook," specifically related to the `useState` Hook.

## Sharing Data Between React Components:
- Methods include props, Context API, state lifting, Redux, and event emitter libraries.

## Three Steps of Refreshing a React UI:
1. State or Prop Update: Modify component data.
2. Re-Rendering: Automatic update based on changed data.
3. Virtual DOM Reconciliation: Efficiently update the actual DOM.

## Triggering Updates After Initial Render:
- Update state or props to trigger updates.

## Recreating DOM Nodes on Every Rerender:
- No, React optimizes using the Virtual DOM.

## After React Updates the DOM:
1. Layout and Paint: Calculate element positions.
2. Reflow and Repaint: Adjust layout and repaint.
3. Frames and Animation: Finalize rendering and animation.
