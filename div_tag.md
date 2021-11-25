## div
- 創造各個不同的區塊進行排版
- 例如: 段落中的**特定文字**做出特效(文字顏色、大小、字型、增加底線、變粗 ... 等)

### Syntax
```
<div id="自訂" class="自訂" style="自訂">內容</div>
```

### 範例格式
```
<p>My name is <span style = 'border : 2px red solid'>Tonny Lee</span>, and my favorite fruit is apple.</p>

...為自訂內容
```

### 範例一: 設計一個有邊框的 div 標籤區塊
```html
<div style = 'border : 2px red solid'>...</div>
```

### 範例二: 設計出有邊框效果的 span 區塊
px 代表邊的長度單位，越大字體越大，線條越粗。
- 1px = 0.04cm
- 1cm = 25px
```html
<span style = 'border : 2px red solid'>...</span>
```

### 範例三: 增加 span 區塊內背景顏色
```html
<span style = 'background-color : green'>...</span>
```

### 範例一: 將部分文字顏色改成藍色
```html
<p>My name is <span style = 'color:blue'>Tonny Lee</span>, and my favorite fruit is apple.</p>
```

### 範例一: 將部分文字顏色改成藍色
```html
<p>My name is <span style = 'color:blue'>Tonny Lee</span>, and my favorite fruit is apple.</p>
```

### 直接把CSS寫入\<span>中
```html
<span style="color:red;">這裡是紅色</span>
```
### 在外部寫 CSS 語法並設定 class
```html
<style>
.effect{
  color:red;
  border:2px red solid
}
</style>

<p>this is <span class = effect>red</span></p>
```
