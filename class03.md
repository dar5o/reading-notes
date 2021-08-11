# Reading notes for class reading 3

>Lists
There are 4 different types of lists
- Ordered Lists
  + an ordered list is created with the `<ol>` element and each item in the list is placed between a `<li>` tag
- Unordered lists
  + an unordered list is created with the `<ul>` element and each item in the list is also placed between a `<li>` tag
- Definition Lists
  + a definition list is created with the `<dl>` element and inside this element you will see pairs of `<dt> and <dd>` elements
- Nested lists
  + you can nest other `<li>` tags within itself and have nested lists

>Boxes
Every box has three properties that can be adjusted to control its appearance
- Border
- Margin
- Padding
The border sepearates the edge of one box to another, margins sit outside the edge of the border, it can be used to create a gap between the borders of two adjacent boxes. Padding is the space between the border of a box and any content contained within it.
You can also hide the visibility of a box with `visibility: hidden;`
*"CSS treats each HTML element as if it has its own box."*
*"You can use CSS to control the dimensions of a box."*
*"You can also control the borders, margins, and padding for each box with CSS."*

>Decisions and loops
an if and else statments check to see if a condition is true, if it resolves to true the first code block is executed, if false, the second block is run instead.
switch statements starts with a variable called the switch value. each case indicates a possible value for this variable and the code that should run if the variable matches that value.
`switch (level) {`
`  case 1:`
`  title = 'Level 1';`
`  break;`

`  case 2:`
`  title = 'Level 2';`
`  break;`

`  case 3:`
`  title = 'Level 3';`
`  break;`
`}`

then there are truthy and falsy values
+ Falsy values:
  - `var highscore = false;`
  - `var highscore = 0;`
  - `var highscore = '';`
  - `var highscore = 10/'score';`
  - `var highscore;`
+ Truthy values:
  - `var highscore = true;`
  - `var highscore = 1;`
  - `var highscore = 'carrot';`
  - `var highscore = 10/5;`
  - `var highscore = 'true';`
  - `var highscore = '0';`
  - `var highscore = 'false';`

loops check a condition. if it returns true, a code block will run until it returns false. there are three common types of loops:
- for
- while
- do while

*"Conditional statements allow your code to make decisions about what to do next."*
*"All values evaluate to either truthy or falsy."*
*"Logical operators allow you to combine more than one set of camparison operators."*


