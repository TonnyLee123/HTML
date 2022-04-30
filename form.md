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
- \<input type="text">
- Displays a single-line text input field
-  to reference form data after a form is submitted.
```html
<form>
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" value="Tony">
</form>
```
### b. Radio Buttons(單選按鈕)
- \<input type="radio">
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
# [其他 form elements](https://www.w3schools.com/html/html_form_elements.asp)
## \<select>
- Drop-down list
```html
<form>
  <label for="cars">Choose a car:</label>
  <select id="cars" name="cars">
    <option value="volvo">Volvo</option>
    <option value="saab">Saab</option>
  </select>
  <input type="submit">
</form>
```
![image](https://user-images.githubusercontent.com/90739897/162145511-3598fc8a-613e-414a-bf56-f9130906b452.png)

## \<textarea>
- Multi-line input field (a text area):
- rows="" (length) 
- cols="" (width)
```html
<form>
  <textarea name="message" rows="10" cols="30">The cat was playing in the garden.</textarea>
  <br><br>
  <input type="submit">
</form>
```
![image](https://user-images.githubusercontent.com/90739897/162146757-56cacc21-f8a7-48f8-a221-3fe5783e8a3f.png)

## \<button>
```html
<button type="button" onclick="alert('Hello World!')">Click Me!</button>
```
![image](https://user-images.githubusercontent.com/90739897/162151763-a7022ea9-8003-4772-8ce4-4f632d2f5627.png) 
按下button後
![image](https://user-images.githubusercontent.com/90739897/162152104-f81af362-f544-48f3-a056-cb62f60a2620.png)

## \<fieldset> and \<legend> 
- \<fieldset>
  - Group related data in a form.
- \<legend>  
  - Defines a caption for the \<fieldset>
```html
<form>
  <fieldset>
    <legend>Personalia:</legend>
    
    <label for="fname">First name:</label><br>
    <input type="text" id="fname" name="fname" value="John"><br>
    <label for="lname">Last name:</label><br>
    <input type="text" id="lname" name="lname" value="Doe"><br><br>
    
    <input type="submit" value="Submit">
  </fieldset>
</form>
```
![image](https://user-images.githubusercontent.com/90739897/162153043-a00d3c5d-283c-478a-8688-5b5bec47975b.png)
