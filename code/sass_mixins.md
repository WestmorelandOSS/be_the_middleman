###### Sass
    @mixin border-radius($radius) {
      border-radius: $radius;
    }
    .box { @include border-radius(10px); }

###### CSS
    .box {
      border-radius: 10px;
    }

