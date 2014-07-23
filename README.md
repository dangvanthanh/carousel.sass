Carousel.sass
=============

**Carousel.sass** is a simple carousel pure css using Sass.

### [DEMO](http://codepen.io/dangvanthanh/full/AgHnB/)

### SASS MIXIN

#### SCSS

``` scss
@mixin carousel($items, $animation: 'default')
```

#### SASS

``` sass
=carousel($items, $animation: 'default')
```

### HTML

``` html
<div class="carousel">
  <input type="radio" id="carousel-1" name="carousel[]" checked>
  <input type="radio" id="carousel-2" name="carousel[]">
  <input type="radio" id="carousel-3" name="carousel[]">
  <input type="radio" id="carousel-4" name="carousel[]">
  <input type="radio" id="carousel-5" name="carousel[]">
  <ul class="carousel__items">
    <li class="carousel__item"><img src="img/carousel-1.jpg" alt=""></li>
    <li class="carousel__item"><img src="img/carousel-2.jpg" alt=""></li>
    <li class="carousel__item"><img src="img/carousel-3.jpg" alt=""></li>
    <li class="carousel__item"><img src="img/carousel-4.jpg" alt=""></li>
    <li class="carousel__item"><img src="img/carousel-5.jpg" alt=""></li>
  </ul>
  <div class="carousel__prev">
    <label for="carousel-1"></label>
    <label for="carousel-2"></label>
    <label for="carousel-3"></label>
    <label for="carousel-4"></label>
    <label for="carousel-5"></label>
  </div>
  <div class="carousel__next">
    <label for="carousel-1"></label>
    <label for="carousel-2"></label>
    <label for="carousel-3"></label>
    <label for="carousel-4"></label>
    <label for="carousel-5"></label>
  </div>
  <div class="carousel__nav">
    <label for="carousel-1"></label>
    <label for="carousel-2"></label>
    <label for="carousel-3"></label>
    <label for="carousel-4"></label>
    <label for="carousel-5"></label>
  </div>
</div>
```

### HOW TO USE


``` scss
@import 'carousel';

@include carousel(5);
```