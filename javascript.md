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
