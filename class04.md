# Reading notes for reading 4

>HTML links
Links are written using the `<a>` element
`<a href ="https://google.com">Google</a>`
The text is what is clickable and the link in the quotation is where you are redirected to.
When linking users to other pages on the same site, you do not need to specify the domain name in the URL.
`<a href="index.html">Home</a>`
To create a link that starts up the users email program and addresses an email to a specified email address, you use malito:
`<a href="malito:example@gmail.com">Email Us</a>`

>Creating site layouts
- Positioning
  + Normal Flow (no code needed)
  + Relative Positioning (`position:relative`)
  + Absolute Positioning (`position:absolute`)
  + Fixed Positioning (`position:fixed`)
  + Floating Elements (`float:`"right, left, top, bottom)

>Generic screen sizes
- Iphone4, resolution **960x640**
- Ipad2, resolution **1024x768**
- 13" macbook, resolution **1280x800**
- avg monitor, resolution **1920x1080**
screen sizes vary so much and because of this, web designers often try to create pages of around 960-1000 pixels wide

>Liquid layouts
liquid layouts use percentages to specify the width of each box so that the design will stretch to fit the size of the screen
other web designers use layout grids to set content on their page. grids set consistent proportions and spaces between content to help create a more professional looking design

*`<div>` elements are often used as sections of a page to better sort content*
*pages can be fixed width or liquid (stretchy) layouts*
*most web designers indicate what the site is about within the top 600 pixels of the web page*
*you can have more than one css style sheet on one web page*

>Functions, methods, and objects
every JavaScript function is actually a Function object. Functions created with the Function constructor do not create closures to their creation contexts; they always are created in the global scope. When running them, they will only be able to access their own local variables and global ones, not the ones from the scope in which the Function constructor was created. This is different from using Global_Objects/eval with code for a function expression. Functions let you group a series of statements together to perform a specific task.
objects are a set of variables and functions that take on new names to create a model of something you would see in the real world.


