# CAI DAT SASS

- can nodejs
- cai `git scm`
- cai dat SASS qua command line `npm i -g sass`
- cau lenh covert tu sass sang css `sass ./app.scss ./css/app.css --watch` --watch de covert tu dong khi luu code.

# DAC DIEM SASS/SCSS

1. su dung bien

```scss
$textColor: red;
p {
  color: $textColor;
}
```

2. Nested code (code long nhau)

```html
<header class="header">
  <div class="header-inner header-inner-text">
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit vero harum
    totam! Illo perferendis sequi expedita enim, debitis excepturi laboriosam
    eos nesciunt iste aliquam? Nobis, pariatur. Magnam debitis ea maiores.
  </div>
</header>
```

```scss
.header {
  color: blue;
  &-inner {
    //header-inner
    color: red;
    &-text {
      color: yellow;
      &:hover {
        //tuong duong .header-inner-text:hover
        color: red;
      }
    }
    &:hover {
      //tuong duong .header-inner:hover
      color: blue;
    }
  }
  &-inner-text {
    color: yellow;
  }
}
```

3. mixin code (mot doan code su dung lai o nhieu noi)

```scss
//khai bao mixin
@mixin nameMixin() {
}
//su dung mixin
@include nameMixin();

//vi du khi khai bao
@mixin bgc($bgcolor) {
  background-color: $bgcolor;
}
//vi du voi khai bao co default
@mixin bgcolord($bgc: red) {
  background-color: $bgc;
}

//vi du voi khai bao default
@mixin size($width, $height: $width) {
  width: $width;
  height: $height;
}

//vd khi su dung
@include bgc(black);
```

3.1 mixin voi dieu kien

```scss
@mixin absoluteCenter($direction: "left") {
  position: absolute;
}
```
