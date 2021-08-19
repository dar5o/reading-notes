# Reading notes for class 9

>Forms
forms serves the most important role of any website. the search bar. most notably the google.com search box. along with inputting text, forms serve other crucial roles:
+ adding text
  - text input
  - password input
  - text area
+ making choices
  - radio buttons
  - checkboxes
  - drop-down boxes
+ submitting forms
  - submit buttons
  - imagine buttons
  - file upload

a forms main role is to recieve information from the user and proceess it to store or send back to the user in a new page. 

form structure
```html
<form action ="http://www.example.com/subscribe.php" method="get">
<p>This is where the form controls will appear. </p>
</form>
```

for text input you use `<input type="text" name="username" size="15" maxlength="30" />`

if you use `type="password"` the input from the user will be masked.
#### more types include :
- "email"
- "url"
- "search"
- "radio"
- "checkbox"
- "file"
- "submit"
- "image"
- "hidden"
- "date"

you can also group form elements together inside the `<fieldset>` element

*information from a form is sent in name/value pairs.*



