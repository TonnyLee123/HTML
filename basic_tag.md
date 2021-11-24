meta_tag
- Define metadata about file
- \<meta charset = 'UTF-8'>
- \<meta name = 'description' content = 'This is an awesome website'>

## 標題及段落
```
1. <h1>...</h1>
- Header 
- h1 ~ h2

2. <p>...</p>
- Paragraph

3. <br/>
- Single tag
- Create new line

4. <hr/>
- Horizontal line
```

## 字型編輯
```
1. <b>...</b>
- Bold Text

2. <i>...</i>
- Italicize

3. <big>...</big>
- 放大字體

4. <small>...</small>
- 縮小字體

5. <sub>...</sub>
- Subscript
- 縮小字體
- <p>H<sub>2</sub>O</p>

6. <sup>...</sup>
- Superscript
- 指數
- <p>10<sup>2</sup></p>
```

## Link
1. \<a href = '網址'>前往新網址的媒介(如文字，照片等等)\</a>
```html
<a href = 'https://www.google.com'> Google's Homepage (text for link)</a>
```
2. Open Link in a new tab
```
attrs = target = '_blank'
```
3. Link to other pages on our website. 
- 注意Page2.html和index.html在同個folder.
```
href = 'page2.html'
```
## 其他標籤
```
1. <!-- ... -->
- Comment
```

# Style & Color
- Change text's color
```html
<p style = 'color : blue'>You can style your HTML.</p>
``` 
- Change background's color
```html
<body style = 'background-color : blue'> ... </body>
```

# Layout
- Formatting a page
```
<body>
  <header>
  
  </header>
  
  <main>
  
  </main>
  
  <footer>
  
  </footer>

</body>
```
- Header
  - Navigation menu 
    - 放各種連結 
```html
<header>...</header>

<header>
   <nav>
     .
     .
     .
   </nav>
</header>
```

- Main Content
```html
<main>

1. <article>...</article>
  
2. <section>...</section>
  
<!--常用於廣告-->
3. <aside>...</aside>
  
</main>
```

- Footer
  - Additional navigational links. 
```html
<footer>...</footer>
```
