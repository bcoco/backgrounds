

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
```
Syntax can live within each line, basically:
```background: 
            url('background1.jpg') no-repeat top left,
            url('background2.jpg') repeat-x bottom center;
        /* Adjust background positions, repeat settings, etc. as needed */
```

## Background Position
first value is horizontal, second is vertical

## gradients
Since so much of this relies on understanding gradients... https://css-tricks.com/a-complete-guide-to-css-gradients/
