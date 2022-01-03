# id Attribute
- 給予element一個獨特id。
- 同個 id 不可以給多個不同元素。
- \#
## 功能一 搭配 CSS
CSS 透過 id 來指定要變style的 element。
``` html
<head>
<style>
#myHeader {
  background-color: lightblue;
  text-align: center;
} 
</style>
</head>

<body>
<h2>The id Attribute</h2>
<p>Use CSS to style an element with the id "myHeader":</p>

<h1 id="myHeader">My Header</h1>
</body>
```
## <a href = 'https://www.w3schools.com/html/tryit.asp?filename=tryhtml_id_js'>功能二 搭配 JavaScript</a>
JavaScript 透過 **getElementById()** access 特定 id 的 element
``` html
<h1 id="myHeader">Hello World!</h1>
<button onclick="displayResult()">Change text</button>

<script>
function displayResult() {
  document.getElementById("myHeader").innerHTML = "Have a nice day!";
}
</script>
```
當按下按鈕時，執行displayResult()。  
displayResult()，透過getElementById("myHeader")找到id為myHeader的元素。  
然後再修改其內容。  
## <a href = 'https://www.w3schools.com/html/tryit.asp?filename=tryhtml_id_bookmark'>功能三 Bookmarks</a>
Allow readers to jump to specific parts of a webpage.
```
<a href="#C4">Jump to Chapter 4</a>
<h2 id="C4">Chapter 4</h2>
```
