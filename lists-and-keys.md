# Reading notes for class 3 of code 301

> lists and keys

.map() creates a new array populated with the results of calling a provided function on every element in the calling array. basically set by whatever code the callback function performs on the original array at that index.

curly braces allow the you to use variable values in JSX.

list items need a unique key for each of them

a key is used as an id for the elements. this is to figure out which of the elements have been changed, added, or removed.

> spread operator

a spread operator is essentially a way to add items to arrays or objects, combining arrays or objects, and spreading an array into arguments for a function. spread can be used instead of Array.slice(). it will create a new array rather than copying the old reference.

a spread operator can:

- add to a react state
- copy an array
- concat arrays
- use array as an argument for a function
- use math functions

example of the spread operator combining two arrays:

`array1And2 = [...array1, ...array2];`

example of the spread operator adding a new item to an array:

`nameArray = ['tom', 'jerry', ...tvShowArray];`

example of the spread operator combining two objects:

`appleObject = {...phoneObject, ...deviceObject, model: "iPhone 13" };`

> passing functions between components

first he creates the function to be passed into the child component from the parent, within the parent component.

`increment` replaces the old array with the new array changing the state of it where the count is increased by 1.

using props, you can pass a method from parent to child component, similar to variables.

using `this.prop.propfromparent`, the child component can access a method that was passed to it from a parent component.

# Things i want to learn more

*advanced techniques of the spread operator*