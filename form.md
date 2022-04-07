# [form](https://www.w3schools.com/html/html_forms.asp)
- Collect user input. 
- The user input is most often sent to a server for processing.
## 1. \<form>
```html
<form>
  ...
</form>
```

## 2. \<label>
- 欄位的名稱
- The **for attribute** == **id attribute**
```html
<form>
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" value="Tony">
</form>
```

## 3. \<input>
### a. Text Fields
- Displays a single-line text input field
```html
<form>
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" value="Tony">
</form>
```
### b. Radio Buttons(單選按鈕)
- 注意 value
```html
<form>
  <input type="radio" id="html" name="fav_language" value="HTML">
  <label for="html">HTML</label><br>
  <input type="radio" id="css" name="fav_language" value="CSS">
  <label for="css">CSS</label><br>
</form> 
```
### c. Checkboxes(複選框)
```html
<form>
  <input type="checkbox" id="vehicle1" name="vehicle1" value="Bike">
  <label for="vehicle1"> I have a bike</label><br>
  <input type="checkbox" id="vehicle2" name="vehicle2" value="Car">
  <label for="vehicle2"> I have a car</label><br>
</form> 

```
### d. The Submit Button
- action attribute
  - The form-data will be sent to a page called "/action_page.php" when click the button.
- name attribute
  - Each \<input> must have a **name attribute** to be submitted.
  - If the name attribute is omitted, the value of the input field will not be sent at all.
```html
<form action="/action_page.php">
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" value="John"><br>

  <input type="submit" value="Submit">
</form> 
```
