# Sass Mixins

Included in this Mixin SASS file is the ability to create:

* Buttons

* CSS Arrows

* Opacity with IE8 support

* Vertical aligned items

* Percentage pie charts which are animated


## Buttons

To use buttons, simple add the following:
```
@include btn(background-color, width, padding, font-size, font-color);

```
So, a realtime example would be:

```
@include btn(#2ecc71, auto, 10px 30px, 16px, #ffffff);
```

## CSS Arrows

To use, add the following to the :before css property
```
@include css-triangle(background-color, arrow-position, size, centered, absolute);
top:100%;
```
So, a realtime example would be:

```
@include css-triangle(#0072ff, down, 30px, true, absolute);
top:100%;
```

## Opacity

To use, add the following
```
@include opacity(0.4);
```

## Vertical Aligned

To use, add the following
```
@include vertical-center;
```


