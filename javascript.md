# addEventListener()
- Attaches an event handler(處理程序) to the specified element.

## <a href = 'https://www.w3schools.com/jsref/tryit.asp?filename=tryjsref_element_addeventlistener'> Attach a **click event** to a button</a>
- 透過 addEventListener()的click event 去觸發後面function
```javascript
<script>
document.getElementById("myBtn").addEventListener("click", function() {
  document.getElementById("demo").innerHTML = "Hello World";
});
</script>
```
# classList 
- returns the class name(s) of an element.
- useful to add, remove and toggle CSS classes on an element.
- read-only, however, you can modify it by using the add() and remove() methods.
## <a href = 'https://www.w3schools.com/jsref/tryit.asp?filename=tryjsref_element_classlist_add'> Add the "mystyle" class to a <div> element:</a>
- 找到ID為myDIV的元素，然後幫它**新增新的class。**
```javascript
document.getElementById("myDIV").classList.add("mystyle");
  ```
