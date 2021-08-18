# Reading notes for class 8 reading

> CSS layout

CSS page layout techniques allow us to take elements contained in a web page and control where they're positioned relative to the following factors: their default position in normal layout flow, the other elements around them, their parent container, and the main viewport/window. 
### For Example:
- Normal flow
- the display property
- Flexbox
- grid
- Floats
- positioning
- Table layout
- multiple-column layout

Flexbox is the short name for the Flexible Box Layout CSS module, designed to make it easy for us to lay things out in one dimension; either as a row or as a column. To use flexbox, you apply `display: flex` to the parent element of the elements you want to lay out; all its direct children then become *flex items.* 

Positioning allows you to move an element from where it would otherwise be placed in normal flow over to another location. Positioning isn’t a method for creating the main layouts of a page; it's more about managing and fine-tuning the position of specific items on a page. 

## Here is a practical positioning example

#### the html portion
```html
  <section class="info-box">
    <ul>
      <li><a href="#" class="active">Tab 1</a></li>
      <li><a href="#">Tab 2</a></li>
      <li><a href="#">Tab 3</a></li>
    </ul>
    <div class="panels">
      <article class="active-panel">
        <h2>The first button</h2>

        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque turpis nibh, porttitor nec venenatis eu, pulvinar in augue. Vestibulum et orci scelerisque, vulputate tellus quis, lobortis dui. Vivamus varius libero at ipsum mattis efficitur ut nec nisl. Nullam eget tincidunt metus. Donec ultrices, urna maximus consequat aliquet, dui neque eleifend lorem, a auctor libero turpis at sem. Aliquam ut porttitor urna. Nulla facilis.</p>
      </article>
      <article>
        <h2>The second button</h2>

        <p>This tab hasn't got any Lorem Ipsum in it. But the content isn't very exciting all the same.</p>
      </article>
      <article>
        <h2>The third button</h2>

        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque turpis nibh, porttitor nec venenatis eu, pulvinar in augue. And now an ordered list: how exciting!</p>

        <ol>
          <li>dui neque eleifend lorem, a auctor libero turpis at sem.</li>
          <li>Aliquam ut porttitor urna.</li>
          <li>Nulla facilis</li>
        </ol>
      </article>
    </div>
  </section>
```
#### now to style with css
```css
/* this will set up sans-serif font on the page */
  html {
    font-family: sans-serif;
  }
/*  use the border-box box-sizing mode */
  * {
    box-sizing: border-box;
  }
/* get rid of body margin */
  body {
    margin: 0;
  }
/* setting properties of our info button/boxes */
  .info-box {
    width: 450px;
    height: 400px;
    margin: 0 auto;
  }
  .info-box ul {
    padding-left: 0;
    margin-top: 0;
  }
  .info-box li {
    float: left;
    list-style-type: none;
    width: 150px;
  }

  .info-box li a {
    display: inline-block;
    text-decoration: none;
    width: 100%;
    line-height: 3;
    background-color: red;
    color: black;
    text-align: center;
  }
  .info-box li a:focus, .info-box li a:hover {
    background-color: #a60000;
    color: white;
  }

  .info-box li a.active {
    background-color: #a60000;
    color: white;
  }
  .info-box .panels {
    height: 352px;
    position: relative;
    clear: both;
  }
  .info-box article {
    position: absolute;
    top: 0;
    left: 0;
    height: 352px;
    padding: 10px;
    color: white;
    background-color: #a60000;
  }

  .info-box .active-panel {
    z-index: 1;
  }
```

if you wanted to make them clickable or for them to do something on the webpage you would need JS for that. this covers styling and making your webpage look presentable.