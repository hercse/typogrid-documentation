# Carousel

The current slideshow allows you to display the font design content more conveniently.

```
<div class="carousel h-50vh ml:h-75vh">
        <div class="carousel-page" slide="0">
            <div class="frame">
            </div>
            <div class="background"></div>>
        </div>
        <div class="carousel-page" slide="1">
            <div class="frame">
            </div>
            <div class="background"></div>>
        </div>
        <div class="carousel-page" slide="2">
            <div class="frame">
            </div>
            <div class="background"></div>>
        </div>
    </div>
```

Please make sure that `.carousel` has width and height. Each page will be separated by `.carousel-page` as the unit. Which uses the `[slide]` property to locate the order of the slides.

### Frame

The built-in frames have `.frame` to place the content and `.background` to display the background respectively. Both of these functions and Usage can be defined, but only `.frame` support animation.

### Animation

If you are in `.frame`, you can use `fadeIn` to apply animation, which will display the animation asynchronously according to the order of the objects.
