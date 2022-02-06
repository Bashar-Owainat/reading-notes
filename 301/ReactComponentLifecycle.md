# React: Component Lifecycle Events
There are three phases of the component lifecycle:
- Mounting: in this phase instances of components are being created and inserted into the DOM.
- Updating: this phase if for updating and state changing
- Unmounting: this phase is for removing a component from the DOM
## general questions
1.	Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
- The render happens first 
2.	What is the very first thing to happen in the lifecycle of React?
- Mounting 
3.	Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
- Constructor, static getDerivedStateFormProps, render, React updates ,componentDidMount and UNSAFE_componentWillUnmount
4.	What does componentDidMount do?
- Used to load anything using a network request or initialize the DOM
