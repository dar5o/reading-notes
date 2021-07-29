[<Go Back](README.md)
#Here are some notes from our javascript lecture
>what is javascript?
+ java script is a programming language that uses class functions and scripts/objects to run environments for webpages and executable files.

>standard objects

+ array
    - Arrays are list-like objects whose prototype has methods to perform traversal and mutation operations. Since an array's length can change at any time, and data can be stored at non-contiguous locations in the array, JavaScript arrays are not guaranteed to be dense; this depends on how the programmer chooses to use them.
    *An example of a common array would be* 
    let fruits = ['Apple', 'Banana']
    console.log(fruits.length)
    and the output would be 2

+ boolean
    - The Boolean object is an object wrapper for a boolean value. IE: True or False variables
    *An example of a common boolean would be* 
    var x = new Boolean(false);
    then you would test this boolean but running
    if (x) {
        // this code is not executed
    }
+ function
    - Every JavaScript function is actually a Function object. Functions created with the Function constructor do not create closures to their creation contexts; they always are created in the global scope. When running them, they will only be able to access their own local variables and global ones, not the ones from the scope in which the Function constructor was created. This is different from using Global_Objects/eval with code for a function expression.
+ string
    - The String object is used to represent and manipulate a sequence of characters.
    *All of these are ways to use the string object*
    const string1 = "A string primitive";
    const string2 = 'Also a string primitive';
    const string3 = `Yet another string primitive`;
    const string4 = new String("A String object");

>next we have statements and declarations

+ if-else
    - The if statement executes a statement if a specified condition is truthy. If the condition is falsy, another statement can be executed.
    *An example of a common if-else statement would be*
    function testNum(a) {
    let result;
    if (a > 0) {
    result = 'positive';
    } else {
    result = 'NOT positive';
    }
    return result;
    }   

    console.log(testNum(-5));

