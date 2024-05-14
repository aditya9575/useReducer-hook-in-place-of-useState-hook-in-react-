# useReducer-hook-in-place-of-useState-hook-in-react-
This is a simple code instruction repo towards understanding the  Implementation of  useReducer hook in comparison to useState hook 


Steps to initialize useReducer hook :

1) start by importing useReducer at the top

2) Now inside the main function above the return statement initialize this useReducer hook with [ state and dispath ] destructuring from the useReducer hook and remember this useReducer hook takes in two arguments 1st is the reducer function , 2nd is the initialState

3) Now inside the component trigger this reducer function whilst simultaneously specifying the action type via ---> dispatch() function
example-> <button onClick={() => dispatch({ type: "Increment" })}>

4) Now we above the component function define our reducer function which takes in the current state state and action as the arguments and then we use if conditioning to check for the action type and then perform some action on the initial state accordingly
    

