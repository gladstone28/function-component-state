[Link to lesson](https://www.codecademy.com/courses/react-101/lessons/the-state-hook/exercises/why-use-hooks)



### The State Hook

**Why Use Hooks?**

What should we do if we want to add a state to our function component? How about if we wanted our app to respond to the changes in data?

In this lesson, we’ll learn about React Hooks and how they can help us powerfully wield function components.

React Hooks, plainly put, are functions that let us manage the internal state of components and handle post-rendering side effects directly from our function components. Using Hooks, we can determine what we want to show the users by declaring how our user interface should look based on the state.

React offers a number of built-in Hooks. A few of these include useState(), useEffect(), useContext(), useReducer(), and useRef(). See the full list in the React docs.

In this lesson, we’ll learn how to:

- Build a “stateful” function component.
- Use the State Hook.
- Initialize a state and set a state.
- Define event handlers.
- Use state setter callback functions.
- Use state with arrays and objects.


### Instructions
Checkpoint 1 Passed

1. Open the AppFunction.js file. We will learn how this code works in the next few exercises. Don’t worry about the details of what is going on here just yet, but take a few moments to read through the definition of this function component and develop some theories about what this code may be doing.

Press “Run” to see how the code behaves!

Default exports can be assigned to any local variable name when they are imported. Switching these two lines of code assigns a different value to the same variable name of App.

In index.js, replace these lines:
```
import App from "./Container/AppClass";
// import App from "./Container/AppFunction";
```
with these lines:
```
// import App from "./Container/AppClass";
import App from "./Container/AppFunction";
```
If you want a review on this, take a look at the lesson on [JavaScript modules](https://www.codecademy.com/enrolled/courses/introduction-to-javascript).

