[教學](https://www.youtube.com/watch?v=_xkSvufmjEs)  
[範本](https://xd.adobe.com/spec/6ebfeb86-6eeb-4b69-77dc-ecf4c4506bcc-188e/screen/530dc661-57b9-43cc-a9c6-e3113aaaec9e/specs/)
### 其他參考資料
[1](https://www.youtube.com/watch?v=K1HchLD6fHI)
[2](https://www.youtube.com/watch?v=tcskp-ncN0I)
[3](https://www.youtube.com/watch?v=r_hYR53r61M)
[4](https://www.youtube.com/watch?v=KgRENOnSCxE)
[5](https://www.youtube.com/watch?v=D-h8L5hgW-w)
[6](https://www.youtube.com/watch?v=1wfeqDyMUx4)
[7](https://www.youtube.com/watch?v=ZFQkb26UD1Y)
[8](https://www.youtube.com/channel/UCvoKIJfodk4IhNAAjrBfx-g)
[9](https://www.youtube.com/watch?v=ZFQkb26UD1Y)
[10](https://www.youtube.com/watch?v=hqYIe5Y76oY)
[11](https://tw.strikingly.com/?utm_source=google-sem&utm_medium=cpc&utm_campaign=v2-s-rest-computers-search-lo-website_category-zhtw&utm_content=v2a-s-rest-computers-search-lo-website_category-category_portfolio_website_v1-zhtw&utm_term=make%20a%20porfolio&gclid=EAIaIQobChMI-7L9-bXJ9AIVosBMAh3g1ArbEAAYASAAEgLKo_D_BwE)
[12](https://www.mockupworld.co/all-mockups/)
```html

<!--Normalize ，針對不同瀏覽器與各版本之間不相容的Tag進行微調
	使不同瀏覽器之間也能呈現相同網頁。-->

<!DOCTYPE html>
<html>
	<head>
		<meta charset = 'UTF-8'>

		<!--使用手機或平板等等裝置打開網頁時，能呈現相對比例的網頁-->
		<meta name = 'viewport' content = 'width = device-width', initial-scale = '1.0'>
		<title>Tonny Lee Portfolio Website</title>
	</head>
	
	<body>
		<!--介绍性内容(Logo，搜索框，作者名稱, 等等)-->
		<hearder>
			<div class = 'logo'>
				<img src = 'https://upload.wikimedia.org/wikipedia/commons/a/ab/Apple-logo.png'>
			</div>
			<!--aria-label: 告訴 '讀屏軟件' 某個元素是什麼(for accessibility)-->
			<button class = 'nav-toggle' aria-label = 'toggle navigation'>
				<span class = 'hamburger'></span>
			</button>			
			<!--提供導航欄連結的區域，這些連結最終抵達的只是當前網頁的某個區塊-->
			<nav class = 'nav'>
				<ul class = 'nav__list'>
					<li class = 'nav__item'><a href = 'ghome' class = 'nav__link'>None</a></li>
					<li class = 'nav__item'><a href = 'g' class = 'nav__link'>My Services</a></li>
					<li class = 'nav__item'><a href = 'g' class = 'nav__link'>About me</a></li>
					<li class = 'nav__item'><a href = 'g' class = 'nav__link'>My Work</a></li>
				</ul>		
			</nav>	
		</hearder>

		<!--introduction-->
		<!--用在 HTML 文件中有明顯含義的-->
		<!--Use id for 'Anchoring'-->
		<section class = 'intro' id = 'home'>
			<h1 class = 'section__title section__title--intro'>
				Hi, I am <strong>Tonny Lee</strong>
			</h1>
			<p class = 'section__subtitle section__subtitle--intro'>front-end dev</p>
			<img src = 'https://megapx-assets.dcard.tw/images/19357807-6860-42a3-b1ec-25384ab32efe/640.jpeg'>
		</section>

		<!--My Services-->
		<section class = 'my-services' id = 'services'>
			<h2 class = 'section__title section__title--services'>What I do</h2>
			<div class = 'services'>
				<div class = 'service'>
					<h3>Design + Development</h3>
					<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
				</div>

				<div class = 'service'>
					<h3>E-Commerce</h3>
					<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
				</div>

				<div class = 'service'>
					<h3>WordPress</h3>
					<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
				</div>
			</div>
			<a href = '#work' class = 'btn'>See my work</a>
		</section>

		<!--About me-->
		<section class = 'about-me' id = 'about_me'>
			<h2 class = 'section__title section__title--about'>Who I am</h2>
			<p class = 'section__subtitle section__subtitle--about'></p>
			<div class = 'about-me__body'>
				<p></p>
				<p></p>
			</div>
			<img src = 'https://obs.line-scdn.net/0hpoMDAGAjL0BwPQR7eylQF0prLC9DUTxDFAt-QzNTcXQICToXS15iLlM0JXENDWgeGVhgIVM1NHENBWEVGVli/w644'>
		</section>

		<!--My work-->
		<section class = 'my-work' id = 'my_work'>
			<h2 class = 'section__title'>My work</h2>
			<p class = 'section__subtitle'>A selection of my range of work</p>

			<div class = 'portfolio'>
				<!--01-->
				<a href = '#' class = 'portfolio__item'>
					<img src = 'https://cf.shopee.tw/file/8b3c82fd7cb19c6f38fe6e9c852ffc5d' class = 'portfolio__img'>
				</a>
				<!--02-->
				<a href = '#' class = 'portfolio__item'>
					<img src = 'https://cf.shopee.tw/file/8b3c82fd7cb19c6f38fe6e9c852ffc5d' class = 'portfolio__img'>
				</a>
				<!--03-->
				<a href = '#' class = 'portfolio__item'>
					<img src = 'https://cf.shopee.tw/file/8b3c82fd7cb19c6f38fe6e9c852ffc5d' class = 'portfolio__img'>
				</a>
				<!--04-->
				<a href = '#' class = 'portfolio__item'>
					<img src = 'https://cf.shopee.tw/file/8b3c82fd7cb19c6f38fe6e9c852ffc5d' class = 'portfolio__img'>
				</a>
				<!--05-->
				<a href = '#' class = 'portfolio__item'>
					<img src = 'https://cf.shopee.tw/file/8b3c82fd7cb19c6f38fe6e9c852ffc5d' class = 'portfolio__img'>
				</a>
				<!--06-->
				<a href = '#' class = 'portfolio__item'>
					<img src = 'https://cf.shopee.tw/file/8b3c82fd7cb19c6f38fe6e9c852ffc5d' class = 'portfolio__img'>
				</a>
				<!--07-->
				<a href = '#' class = 'portfolio__item'>
					<img src = 'https://cf.shopee.tw/file/8b3c82fd7cb19c6f38fe6e9c852ffc5d' class = 'portfolio__img'>
				</a>
				<!--08-->
				<a href = '#' class = 'portfolio__item'>
					<img src = 'https://cf.shopee.tw/file/8b3c82fd7cb19c6f38fe6e9c852ffc5d' class = 'portfolio__img'>
				</a>
			</div>
		</section>

		<!--mailto:-->
		<footer>
			<a href = 'mailto: a91802tony@gmail.com' class = 'footer__link'>a91802tony@gmail.com</a>

			<ul class = 'social-list'>
				<li class = 'social-list__item'><a href = '#' class = 'social-list__link'>a</a></li>
				<li class = 'social-list__item'><a href = '#' class = 'social-list__link'>b</a></li>
				<li class = 'social-list__item'><a href = '#' class = 'social-list__link'>c</a></li>
				<li class = 'social-list__item'><a href = '#' class = 'social-list__link'>d</a></li>
			</ul>
		</foolter>
	</body>
</html>
```
### css
```css
*,
*:: before,
*:: after{

	box-sizing: border-box;
}

// Set up custom properties
:root{
	--font-family-primary: ;
	--font-family-secondary: ;

	--font-width-regular: 300;
	--f-bold: 900;

	-- clr-background: #fff;
	-- clr-text: #303030;
	-- clr-accent:  #16e0bd;

	--font-size-h1: 3rem;
	--font-size-h2: 2.25rem;
	--font-size-h3: 1.25rem;
	--font-size-body: 1rem;
}










body{
	background: var(--clr-dark); 
}
```

### @media
- used in media queries to apply different styles for different media types/devices.

Media queries can be used to check many things, such as:

- width and height of the viewport
- width and height of the device
- orientation (is the tablet/phone in landscape or portrait mode?)(方向（平板電腦/手機處於橫向還是縱向模式？）)
- resolution
Using media queries are a popular technique for delivering a tailored style sheet(提供定制的樣式表) (responsive web design) to desktops, laptops, tablets, and mobile phones.

You can also use media queries to specify that certain styles are only for printed documents or for screen readers (mediatype: print, screen, or speech).

Media features provide more specific details to media queries, by allowing to test for a specific feature of the user agent or display device. 
- For example, apply styles to only those screens that are greater, or smaller, than a certain width.
