###### Sass(SCSS)
    $base_color: black;
    .thing{
      color: $base_color;
      .nested-thing{
        color:lighten($base_color, 10%)
      }
    }

###### CSS
    .thing {
      color: black;
    }
    .thing .nested-thing {
      color: #1a1a1a;
    }
