# Reading notes for class 2 of 301

> react component diagram
[React: Component Lifecycle events](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

based off the diagram, 'render' would happen before 'comopnentDidMount.'

the first thing to happen in the lifecycle of react is the constructor

order of how things happen:

- constructor
- render
- componentDidMount
- react updates
- componentWillUnmount

componentDidMount will run a method after mounting, load anything requiring a network request or initialize the DOM.

> state vs props

props can be anything you want passed down from the parent to the child, similar to function arguments. props are passed into a component while state is what stays in the component.

we re-render our application whenever state is changed.

what can be stored in state:

- checkbox
- input element
- anything inside of a component
- form

# Things i want to learn more about 

*how state is used in code and its typical uses*
*react lifecycle methods*
*unmounting components*