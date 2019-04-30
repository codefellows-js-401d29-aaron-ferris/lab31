![cf](http://i.imgur.com/7v5ASc8.png) Lab 31: Application State
============================================================================  
Date: April 29th, 2019  
Author: Aaron Ferris
  
UMLs Completed with: Erin Trainor, Jon Gentry, Cory Henderson  
  
[LAB INSTRUCTIONS](./LAB.md)
  
## Part 1: Connect to a Store  
  
[part 1 Details](./PART1.md)  
  
### Sandbox Submission
  
[part one sandbox](https://codesandbox.io/s/n771jx0mz0)  

  
## Tasks
  
[x] You've been provided starter code to work with - `app-state-connect`  
[x] Connect `index.js` to the redux store and pass it down to the `App` component  
[x] Remove the state declaration in the constructor  
  [x] Do you still need a constructor? if it's a function no, if it's a component maybe?   
[x] Bring in the actions to `app.js`  
[x] Map state and dispatch to props in `app.js`  
  [x] use `stuff` as your state keyword.  
[x]  Export the connected `App` component  
[x]  Render `this.props.stuff.foo` instead of `this.state.foo`  
[x] Remove the `handleChange()` method in `app.js`  
[x] Re-Implement the click event on the `<div>` using the action method that you mapped earlier  
  
## UML
[Part 1 UML](./lab31p1uml.jpg)

## Part 2: Create a new Reducer

### Sandbox Submission
[part two sandbox](https://codesandbox.io/s/8nm55owl60)

## Tasks
[x] Fork this sandbox: starter code: app-state - reducers   
[x] Create a new numbers reducer in the store: numbers-reducer.js  
[x] Create a new numbers action in the store: numbers-actions.js  
  [x] Create a new action creator for the "RESET" action  
[x] Connect to the reducer in the store's index.js file and export it's state as "numbers"  
  [x] The initial state should be a simple object with one key: currentNumber, set to any number you would like  
[x] In the reducer, create a listener (in the case) for both the CHANGE and RESET actions  
  [x] On CHANGE, change the number to a random number  
  [x] On RESET, reset the state back to the initialState  
[x] Create a new Numbers component that renders a <div> with the content "Hello"  
[x] Import this into your <App> and render it below the content already being rendered  
  [x] You should see your app's output along with "Hello" at this point  
[x] Import your numbers actions  
[x] Connect the Numbers component to the store and map the numbers actions and state to Props.  
[x] Render this.props.numbers.currentNumber 
   
## UML
[Part 2 UML](./lab31p2uml.jpg)

