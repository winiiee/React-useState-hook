# React-useState 
A minor project(BMI Calculator) using react useState and some conditionals


1)useState
- A container for a piece of data that can change over time.
- It allows us to add a state to our functional components.
- A way to manage data that can change over time and component re-renders when the state changes
  
2)How to use it?

i)Import

-import it from the ‘react’ library

  import { useState } from ‘react’ ;
  
ii) Initialize State

-initialize state by calling ‘useState’ function within the functional component

-this function takes an initial value as an argument and returns an array with two elements: current state and a function to update that state

const[count, setCount] = useState(0);

count is the current state 

setCount is a function that updates the count state

3)Where to use?

-use the state in the component’s JSX or logic


