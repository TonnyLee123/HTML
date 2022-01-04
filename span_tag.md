## Span
- 讓我們輕易的修改網頁中的各種小區塊
- 例如: 段落中的**特定文字**做出特效(文字顏色、大小、字型、增加底線、變粗 ... 等)

### Syntax
```
<span style="樣式設計">欲修改內容</span>
```

### 格式
```
<p>My name is <span style = 'border : 2px red solid'>Tonny Lee</span>, and my favorite fruit is apple.</p>
```

### 範例一: 改變部分文字顏色
```html
<span style = 'color:blue'...</span>
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
# Block
- Start new line
