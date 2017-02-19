# slide-menu
> Pure CSS3 sliding menu

## Build
#### Download repo

```sh
$ git clone https://github.com/pradeep1991singh/slide-menu.git
```

#### Generate styles

```sh
$ cd slide-menu
$ npm install
$ gulp dist
```

## Usage

#### Copy/Paste `dist` folder in your project And then add css file in head tag of html file

```html
<link rel="stylesheet" href="dist/styles.css">
```

#### Then add sliding menu template

```html
<header>
	<div class="sliding--menu__wrapper">
		<input type="checkbox" id="navigation" />        
		<label id="hamburger--icon" for="navigation">
			<span class="icon-menu"></span>
		</label>      

		<nav>
			<ul>
				<li><img class="site--logo" src="dist/images/logo.png" alt="site-logo" /></li>        
				<li>
					<a href="#">Home</a>
					<a href="#">About us</a>
					<a href="#">Contact us</a>
				</li>
			</ul>
		</nav>

		<div class="obfuscator">
		</div>        
	</div>
<header>
```

## Demo

[Demo] (https://htmlpreview.github.io/?https://raw.githubusercontent.com/pradeep1991singh/slide-menu/master/index.html)

## License
Copyright (c) 2016, pradeep singh

Permission to use, copy, modify, and/or distribute this software for any
purpose with or without fee is hereby granted, provided that the above
copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES
WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF
MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR
ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN
ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF
OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
