###### SCSS(SCSS)
    $base_color: black;
    .thing{
      &.nested-thing{
        background: lighten($base_color, 10%);
      }
    }
###### CSS With Ampersand
    .thing.nested-thing {
      background: #1a1a1a;
    }
###### CSS Without Ampersand
    .thing .nested-thing {
      background: #1a1a1a;
    }
