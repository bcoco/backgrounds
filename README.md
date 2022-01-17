# backgrounds
multiple backgrounds, etc.

## Multiple Background CSS
```/* Working method */
.tinted-image {
  background: 
    /* top, transparent red, faked with gradient */ 
    linear-gradient(
      rgba(255, 0, 0, 0.45), 
      rgba(255, 0, 0, 0.45)
    ),
    /* bottom, image */
    url(image.jpg);
}

## Background Position
first value is horizontal, second is vertical
