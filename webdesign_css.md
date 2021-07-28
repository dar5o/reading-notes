#Here are some reading notes for our CSS reading
>what is css?
+ css stands for cascading style sheets and it allows you to create good looking web pages into great looking web pages

css can be used for very basic document text styling, for example, changing the color and size of headings or links. it can also be used to create a layout. for example you can turn a single column of text into a layout with a main content area and a sidebar for related info. it can even be used for effects such as animation.

#css syntax
>  h1 {
>    color: red;
>    font-size: 5em;
>}

h1 would be the header and here what was edited was the color and size.
there are also different ways to insert css. first one being external css.
+ to link your css externally you need to define it with the <img src= "C:\Users\dario\Downloads\download.png" alt ="<link>"> element within the head section of an HTML page. 
><img src= "C:\Users\dario\Downloads\download.png" alt ="<link rel='stylesheet' href='mystyle.css'>">

+ next is internal css, internal css is defined within the <img src= "C:\Users\dario\Downloads\download.png" alt ="<style>"> element within the head section of an HTML page.
>body {
>  background-color: linen;
>}
>
>h1 {
>  color: maroon;
>  margin-left: 40px;
>}

+ finally the last way to implement css is inline css, you define it within the "style" attribute of the relevant element. 
><img src= "C:\Users\dario\Downloads\download.png" alt ="<h1 style='color:blue;text-align:center;'>This is a heading</h1>">
