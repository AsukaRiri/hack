# html-css-hack

[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#links)

[browserhacks](http://browserhacks.com/)

[caniuse](http://caniuse.com/)

[CSS Gradient Generator](http://www.colorzilla.com/gradient-editor/)

[HTML5 Cross Browser Polyfills](https://github.com/Modernizr/Modernizr/wiki/HTML5-Cross-Browser-Polyfills)

```HTML
<link rel="stylesheet" media="all and (orientation:portrait)" href="portrait.css">    // 竖放加载
<link rel="stylesheet" media="all and (orientation:landscape)"href="landscape.css">   // 横放加载
<style media="all and (orientation:portrait)" type="text/css">
  #landscape { display: none; }
</style>
<style media="all and (orientation:landscape)" type="text/css">
  #portrait { display: none; }
</style>
```

```HTML
<meta name="viewport" content="width=320">
<meta name="viewport" content="width=640, maximum-scale=1.0, user-scalable=no">
<meta name="viewport" content="maximum-scale=1.0, user-scalable=no, width=device-width">
```

```HTML
<link rel="stylesheet" media="screen and (-webkit-device-pixel-ratio: 0.75)" href="ldpi.css" />
<link rel="stylesheet" media="screen and (-webkit-device-pixel-ratio: 1.0)" href="mdpi.css" />
<link rel="stylesheet" media="screen and (-webkit-device-pixel-ratio: 1.5)" href="hdpi.css" />
<link rel="stylesheet" media="screen and (-webkit-device-pixel-ratio: 2.0)" href="retina.css" />
```

```css
@font-face {
  font-family: HelveticaRoman;
  src: url('../fonts/HelveticaLTStd-Roman.eot');
  src: local('☺'), url('../fonts/HelveticaLTStd-Roman.woff') format('woff'), url('../fonts/HelveticaLTStd-Roman.ttf') format('truetype'), url('../fonts/HelveticaLTStd-Roman.svg') format('svg');
}
```

```css
@media screen and (max-width: 1024px) {
}
@media screen and (max-device-width: 480px) {
}
```

```css 
@media screen and (-webkit-min-device-pixel-ratio: 2) {
  .bg{
    background-image: url(tiger-2x.png);    
  }
}

.bg{
  background-image: -webkit-image-set(url(tiger.png) 1x, url(tiger-2x.png) 2x);
  background-size: 400px 250px;
}
.bg{
  background-size: cover;
  -ms-behavior: url(css/backgroundsize.min.htc);
  behavior: url(css/backgroundsize.min.htc);
}
```

```css
body
{
    -webkit-overflow-scrolling: touch;
}
```

```css
html {
  -ms-touch-action: manipulation;
  touch-action: manipulation;
}
```

[Others](https://github.com/RubyLouvre/mobileHack)

[创建插件](https://gist.github.com/quexer/3619237)
