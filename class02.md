# Reading notes for reading 2

>HTML and Markup
when adding content to a page you use tags known as markup
- strucural markup
  + the elements you use for both headings and paragraphs
- semantic markup
  + provides extra information such as where emphasis is placed in a sentance, that something you have written is a quotation, the meaning of acronyms, ect

html has six levels of headings: `<h1><h2><h3><h4><h5><h6>`. each heading goes down in size as the number goes up. 
then there are paragraphs: `<p>`. by default, a browser will show each paragraph  on a new line with some space between it and any subsequent paragraphs.
html markup includes special "elements" such as `<head>, <title>, <body>, <header>, <footer>, <article>, <section>, <div>, <span>, <img>, <aside>, <audio>, <canvas>, <datalist>, <details>, <embed>, <nav>, <output>, <progress>, <video>, <ul>, <ol>, <li>` and many others.

>CSS
>>"CSS allows you to create rules that specify how the conetent of an element should appear"

learning CSS mostly involvees learning the different properties you can use. 
basic styles include
- width and height
- borders (color, width, and style)
- background color and images
- position in the browser window
- typeface
- size
- color
- italics, bold, uppercase, lowercase, small-caps

css can be used for very basic document text styling, for example, changing the color and size of headings or links. it can also be used to create a layout. for example you can turn a single column of text into a layout with a main content area and a sidebar for related info. it can even be used for effects such as animation.
- external css
  + to link your css externally you need to define it with the `<link>` element within the head section of an HTML page.
- internal css
  + you can include css rules within a `<style>` element

css treats each html element as if it appears inside its own box and uses rules to indicate how that element should look

>JavaScript
- java script is a programming language that uses class functions and scripts/objects to run environments for webpages and executable files.
  + a script is a series of instructions that a computer can follow one-by-one 
  + a comment can be added to explain what your code does, they make your code easier to read and understand
  + variables are bits of information that can be used in scripts to get the job done
    - variables have different data types 
      + numeric
      + string
      + boolean
    - an array is a special type of variable, it stores a list of values not just one

loops can be used to check through arrays and match a value with an input from the user