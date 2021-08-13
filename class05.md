# Reading notes for reading 5

>Images
images are a powerful tool to convey the tone for your website in less time than it takes to read a description.
images should be:
- relevant
- convey info
- convey the right mood
- instantly recognizable
- fit the color palette

if you are building a site from scratch, it is a good idea to create a folder for all of the images you are going to use.
adding images is as easy as using the `<img>` element. this is an empty element which means there is no closing tag, it carries two attributes:
- src
- alt

src tells the browser where it can find the image file. for example `<img src="images/duck.jpg" alt="A duck">` while the alt attribute provides a text description of the image.
you can also set the height and width of images as well as a title.

image formats
- jpeg
- gif
- png

>Color
color can be used to bring your webpage to life.
the color property allows you to specify the color of text inside an element, you can specify coor in CSS in one of three ways:
- rgb values
- hex codes
- color names

background-color sets the color of the background for a box or your whole site.
hsl allows you to specify colors using hue, saturation, and lightness values.
- hue
  + this is expressed as an angle (between 0 and 360)
- saturation
  + this is expressed as a percentage
- lightness
  + this is expressed as a percentage with 0% being white, 50% being normal and 100% being black

*"it is important to ensure that there is enough contrast between any text and the background color" (otherwise people will not be able to read your content)*

>Text
the apperance of your text can be split into two groups:
- those that directly affect the font and its appearance, i.e: whether its regular, bold, italic, and the size of the text
- those that would have the same effect on text no matter what font you were using, i.e: the color of the text and the spacing between words and letters

typeface terminology
- serif
  + georgia
  + times
  + times new roman
- sans-serif
  + arial
  + verdana
  + helvetica
- monospace
  + courier
  + courier new
- cursive
  + comic sans ms
  + monotype corsiva
- fantasy
  + impact
  + haettenschweiler
- weight
  + light
  + medium
  + bold
  + black
- style
  + normal
  + italic
  + oblique
- stretch
  + condensed
  + regular
  + extended

the font-family property allows you to specify the typeface that should be used for any text inside the element to which a CSS rule applies.
`font-family: Georgia, Times, serif;`

the font-size property enables you to specify a size for the font. there are several ways to specify the size of a font
- pixels
  + `font-size: 12px;`
- percentages
  + `font-size: 200%;`
- ems
  + `font-size: 1.3em;`

*"if you want to use a wider range of typefaces there are several options, but you need to have the right license to use them."*