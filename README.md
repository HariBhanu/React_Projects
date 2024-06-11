# React_Projects
ReactJS Interview Questions

**Q1. What are Higher-Order Components?**

A higher-order component is a function that takes another component and returns a new component.  
We call them Pure Components as they can accept any dynamically provided components, but they won't modify or copy any behavior from their input components.
Using HOC will help us in
1) Code Reusability, Logic and BootStrap abstraction
2) State Abstraction and Manipulation
3) Props Manipulation

**Q2. What is Lifting State up in React?**

When Two or more components at same level are using or sharing the same state then we should lift up the state to the closest common Ancestor
This means that we won't have to maintain a local state in both of them rather we can lift up the State to the parent Component 
