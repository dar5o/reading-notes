# Reading notes for class 4 of 301

> react and forms

a controlled component is an input form element where the value of said element is controlled by react.
the component that controls the render of said form also controls what happens in the form on user input.

storing the user response is more useful to do on submit, otherwise the value is updated within every keystroke. 

`this.setState({value: event.target.value});` allows you to target what the user is entering with an event handler or input field. 

> conditional (ternary) operator

with the ternary operator, you are allowed to have more functionality with less code involved.

the following code is rewritten using a ternary statement:

**original code**:
```js
if(x===y){
  console.log(true);
} else {
  console.log(false);
}
```

**ternary statement**:
```js
x === y ? console.log(true) : console.log(false)
```

# Things i want to learn more about

*can you render 3d objects using react?*

