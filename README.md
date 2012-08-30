eta-filter-mixins
=================

A project for various SCSS mixins 

- currently supports Grayscale, Sepia, Hue-rotate, Brightness, Contrast and Blur

(Saturate and Invert filters coming soon)


How to use:

Grayscale takes a percentage
@include grayscale(100%);

Sepia takes a percentage
@include sepia(100%);

Hue-rotation takes an angle
@include hue-rotate(45deg);

Brightness takes a percentage
@include brightness(100%);

Contrast takes a percentage
@include contrast(100%);

Pass a length in pixels
@include blur(10px);
