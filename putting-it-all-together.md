# Reading notes for class 5 of 301

>thinking in react

the single responsibility prinicple applies to components because a component should only do one thing, provide functionality to child/sub-components.

a static version of an application takes your data model and renders the UI with no clickable or interactive features. 

once the static application is done, your next step would be to add the interactivity.

three questions to detirmine if something is state:

- does it remain a single value over time? if yes: it probably isnt state
- is it passed in from a parent component via props? if yes: it isnt state
- is it computable based on other state/props in your component? if yes: it  isnt state.

the most obvious element of state that we have beyond the form elements is the data model itself. a good idea of where state is in the product component you are trying to give to the customer. another one would be to figure out every component that renders something based on that state. 

> higher-order functions

a higher-order function operates on other functions by taking the fucntions as arguments or returning them.

the greaterThan function is an arrow function that evaluates if a undefined variable is greater than n.

reduce executes the callback function on each member of the calling array which results in a single output value. The reduce method accepts two parameters: 
- The reducer function (callback)
- and an optional initialValue

# Things i want to learn more about