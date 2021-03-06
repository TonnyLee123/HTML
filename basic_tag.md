## meta
- Define metadata about file
```html
<meta charset = 'UTF-8'

<!--讓別人知道關於網站的一些資訊-->
<meta name = 'description' content = 'This is an awesome website'>
<meta name = 'author' content = 'Tonny'>

<!--Control how website is displayed on different devices.-->
<meta name = 'viewport' content = 'width=device-width, initial-scale=1.0'>
```
## 1. Headings and Paragraphs
```
1. <h1>...</h1>
- Header 
- h1 ~ h6

2. <p>...</p>
- Paragraph

3.<pre>...</pre>
- Preformatted Text
- Fixed-width font
- Preserves spaces and line breaks

4. <br>
- Single tag
- Create new line

5. <hr>
- Horizontal line
```
範例
```html
<h1>Heading 1</h1>
<p>This is a paragraph.</p>

<hr>

<h2>Heading 2</h2>
<p>This is <br>a paragraph.</p>

<hr>

<pre>
My Bonnie lies over the ocean.
 My Bonnie lies over the sea.

  My Bonnie lies over the ocean. 
   Oh, bring back my Bonnie to me.   
</pre>
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
attrs => target = '_blank'
```
3. Link to other pages on our website. 
- 注意Page2.html和index.html在同個folder.
```
href = 'page2.html'
```

## Image
1. \<img src = 'location of img'>\</img>
```html
<!-- link to images that are on Internet-->
<img src = 'https://lastfm.freetls.fastly.net/i/u/770x0/16e4fa745320b89781aec0536bd982d6.jpg'></img>

<!-- link to images that are on our computer -->
<!--- 注意Scrime.jpg和index.html在同個folder-->
<img src = 'Scrime.jpg'></img>

```
2. Show the text when the image don't show up because of some error.
```html
attrs => alt = 'This is a person.'
```
3. Adjust height/width and Aspect Ratio(縱橫比)
- 若只調整寬或高其中一個，點腦會自動依照Aspect Ratio設定另外一個值。
```
attrs => height = '50'
attrs => width = '50'
```

## Include (YT) Video into website 
1. \<video src = 'location of file'>...\<video>
```html
<!--加入 controls 才會顯示播放以及其他控制功能-->
<video src = "1000_rounds.mp4" controls></video>
```
2. 自動播放
- autoplay
```html
<video src = "1000_rounds.mp4" autoplay controls></video>
```
3. 重複播放
- loop
<video src = "1000_rounds.mp4" loop controls></video>

4. 調整影片的size
```
attrs => width = '300 (pixels)'
```
5. Thumbnail(縮圖)
- 影片開始前所顯示的圖片
```
attrs => poster = 'Scrim.jpg'
```

6. 載入YT影片
- 對影片點右鍵
- Copy embed code
  - <iframe>...</iframe>
  - 可更改<iframe>裡的內容
- Paste到HTML裡
***
- <iframe src = 'http://....'>...</iframe>
  - Display another website inside of your web page.

## List 
- Unorder List
  ```html
  <ul>
    <li>xxxxx</li>
    <li>yyyyy</li>
    <li>zzzzz</li>
  </ul>
  ```
- Order List
  ```html
  <ol>
    <!--list items-->
    <li>xxxxx</li>
    <li>yyyyy</li>
    <li>zzzzz</li>
  </ol>
  ```
  - attrs => type = 'A'
- Description list
  - Description Term
  - Describe DT
```html
  <dl>
    <dt>Apples</dt>
    <dd>They are sweet!!</dd>
    <dt>Oranges</dt>
    <dd>They are from TW!!</dd>
    
  </dl>
  ```
## Table
- \<caption> Table標題 \</caption>
- \<tr>...\</tr> (table row)
***
- \<th>...\</th> (table header)
- \<td>...\</td> (table data) -> column
***
- \<thead>...\</thead> 
  - 用於方便查看，並無其他功能。
- \<tbody>...\</tbody>
  - 用於方便查看，並無其他功能。
```html
<table>
  <thead>
    <caption> This is title of the table!!! </caption>
    <!--first row with three column (title )-->
    <tr>
      <th>name</th>
      <th>age</th>
      <th>birth_date</th>  
    </tr>
  </thead>
  
  <tbody>
  <!--second row with three column-->
    <tr>
      <td>Tonny_Lee</td>
      <td>20</td>
      <td>2021-10-03</td>  
    </tr>
  </tbody>
</table>
```
## span % div
- Two ways to display HTML elements
  - block element 
  - inline
```html
<!--lnline elements: 第二個連結在第一個連結的旁邊-->
<a href = '#'>link1</a>
<a href = '#'>link2</a>

<!--block elements第二個段落在第二個段落的下面-->
<p>Paragraph</p>
<p>Paragraph</p>
```
- span
  - inline container
```html
<span>link1</span>
<span>link2</span>
```
  - 功能: 顏色部分文字內容，以及其他(如字體大小，粗體等等)
 ```html
 <p>My name is <span style = 'color:blue'>Tonny Lee</span>, and my favorite fruit is apple.</p>
 ```
- div
  - block container
```html
<div>Paragraph1</div>
<div>Paragraph2</div>
```
  
## Input % Forms
- JavaScript 
- 之後再學
## 其他標籤
```
1. <!-- ... -->
- Comment
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
[Reference](https://www.youtube.com/watch?v=pQN-pnXPaVg 'Reference')

