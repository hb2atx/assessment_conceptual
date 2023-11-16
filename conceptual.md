### Conceptual Exercise

Answer the following questions below:

- What is React? When and why would you use it?
React is a front-end language based off of Javascript priciples. You would use it for large scale front-end programs.

- What is Babel?
Babel is a javascript transpiler that allows you to use future javascript in today's browsers.

- What is JSX?
JSX allows us to write HTML in React

- How is a Component created in React?
You create a component with a class or a function and you can render components in the return

- What are some difference between state and props?
Props- Props is short for properties and they are used to pass data between React components
State- React has another special built-in object called state, which allows components to create and manage their own data.
So unlike props, components cannot pass data with state, but they can create and manage it internally.

- What does "downward data flow" refer to in React?
In React, data is passed between components in a unidirectional way.This means that the components must 
be composed in a way such that data is passed top-to-bottom — i.e. in one direction, from the parent component 
down to its children and so on

- What is a controlled component?
is one that takes its current value through props and notifies changes through callbacks like onChange. A parent 
component "controls" it by handling the callback and managing its own state and passing the new values as props 
to the controlled component. You could also call this a "dumb component".

- What is an uncontrolled component?
 is one that stores its own state internally, and you query the DOM using a ref to find its current value when 
 you need it. This is a bit more like traditional HTML.

- What is the purpose of the `key` prop when rendering a list of components?
The key prop is an attribute used when rendering lists of elements. For example if you are iterating .map the key prop will
identify which items have changed.

- Why is using an array index a poor choice for a `key` prop when rendering a list of components?
It could create issues when the lists get modified.

- Describe useEffect.  What use cases is it used for in React components?
useEffect is a hook. When you need to repeat a function for components useEffect is helpful. It helps manage side effects in components. Fetching data from an API is a common usecase.

- What does useRef do?  Does a change to a ref value cause a rerender of a component?
is a hook that provides a way to create a mutable reference that persists across component renders.

- When would you use a ref? When wouldn't you use one?
Use case for useRef is to reference and interact with DOM elements.

- What is a custom hook in React? When would you want to write one?
A custom hook is used for creating functions that are repeated in different components.