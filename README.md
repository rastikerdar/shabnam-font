<h1 id="shabnam-font">Shabnam Font</h1>
<p>A Persian (Farsi) Font</p>
<p dir="rtl">فونت (قلم) فارسی شبنم</p>
<p dir="rtl"><a href="http://rastikerdar.github.io/shabnam-font/">نمایش فونت</a></p>
<p dir="rtl">با تشکر از برنامه <a href="https://fontforge.github.io">FontForge</a></p>
<p dir="rtl">بر مبنای <a href="http://rastikerdar.github.io/vazir-font/" dir="rtl">فونت وزیر</a></p>
<h2 id="-" dir="rtl">طریقه استفاده در صفحات وب:</h2>

<p dir="rtl">
کد زیر را در قسمت style یا فایل css وارد نمایید:
</p>


```css
@font-face {
  font-family: Shabnam;
  src: url('Shabnam.eot');
  src: url('Shabnam.eot?#iefix') format('embedded-opentype'),
       url('Shabnam.woff') format('woff'),
       url('Shabnam.ttf') format('truetype');
  font-weight: normal;
}
      
@font-face {
  font-family: Shabnam;
  src: url('Shabnam-Bold.eot');
  src: url('Shabnam-Bold.eot?#iefix') format('embedded-opentype'),
       url('Shabnam-Bold.woff') format('woff'),
       url('Shabnam-Bold.ttf') format('truetype');
  font-weight: bold;
}

@font-face {
  font-family: Shabnam;
  src: url('Shabnam-Light.eot');
  src: url('Shabnam-Light.eot?#iefix') format('embedded-opentype'),
       url('Shabnam-Light.woff') format('woff'),
       url('Shabnam-Light.ttf') format('truetype');
  font-weight: 300;
}
```

## Install

Grab the [latest release](https://github.com/rastikerdar/shabnam-font/releases/latest) file.

Or you can get it on bower:

```
bower install shabnam-font --save
```

Or [RawGit](https://rawgit.com) CDN:

```html
<link href="https://cdn.rawgit.com/rastikerdar/shabnam-font/v[X.Y.Z]/dist/font-face.css" rel="stylesheet" type="text/css" />
```

Replace [X.Y.Z] with the latest version (e.g. 1.1.0) and integrate the font into your CSS:

```
font-family: 'Shabnam', sans-serif;
```

