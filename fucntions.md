[<Go Back](README.md)
#Here are some notes for our functions reading
> ##JavaScript has the following types of operators. 
+ Assignment operators
+ Comparison operators
+ Arithmetic operators
+ Bitwise operators
+ Logical operators
+ String operators
+ Conditional (ternary) operators
+ Comma operators
+ Unary operators
+ Relational operators

> Functions are one of the fundamental building blocks in JavaScript. A function in JavaScript is similar to a procedure—a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take some input and return an output where there is some obvious relationship between the input and the output. To use a function, you must define it somewhere in the scope from which you wish to call it.

To make a function we are going to need a couple things
+ first being the name of the function
+ a list of paramaters to the function, enclosed in a parantheses and separated by commas
+ the javascript statements that define the function, enclosed in curly brackets

> ##for example
>>function square(number) {
>>  return number * number;
>>}

> ##The control flow is the order in which the computer executes statements in a script.

>> ##for example
>>> imagine a script used to validate user data from a webpage form. The script submits validated data, but if the user leaves a required field empty, the script prompts them to fill it in. To do this, the script uses a conditional structure or if...else, so that different code executes depending on whether the form is complete or not:
>>>>if (field==empty) {
    promptUser();
} else {
    submitForm();
}