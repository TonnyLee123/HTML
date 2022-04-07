# form
Used to collect user input. The user input is most often sent to a server for processing.

## \<input>
```
<input type="text">	Displays a single-line text input field
<input type="radio">	Displays a radio button (for selecting one of many choices)
<input type="checkbox">	Displays a checkbox (for selecting zero or more of many choices)
<input type="submit">	Displays a submit button (for submitting the form)
<input type="button">	Displays a clickable button
```
## Name Attribute
- Each \<input> field must have a **name attribute** to be submitted.
- If the name attribute is omitted, the value of the input field will not be sent at all.
## Text Fields
## \<label>
The **for attribute** of the <label>  == **id attribute** of the <input>.
```html
<form>
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" value="Tony">
</form>
```
## Radio Buttons
- 單選按鈕
- 注意 value
```
<form>
  <input type="radio" id="html" name="fav_language" value="HTML">
  <label for="html">HTML</label><br>
  <input type="radio" id="css" name="fav_language" value="CSS">
  <label for="css">CSS</label><br>
</form> 
```
## Checkboxes(複選框)
```html
<form>
  <input type="checkbox" id="vehicle1" name="vehicle1" value="Bike">
  <label for="vehicle1"> I have a bike</label><br>
  <input type="checkbox" id="vehicle2" name="vehicle2" value="Car">
  <label for="vehicle2"> I have a car</label><br>
</form> 

```
## The Submit Button
The form-data will be sent to a page called "/action_page.php" when click the button.
```html
<form action="/action_page.php">
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" value="John"><br>

  <input type="submit" value="Submit">
</form> 
```
