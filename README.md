# slider
slider on native JavaScript.

The slider has a number of settings, such as adding points, counter and progress lines.

The slider is responsive for different screen resolutions.

### [Example](https://codepen.io/thesanches/pen/KKMgNJw)

## HTML ##
To initialize the slider, you need to set your class to the parent block `<div class="slider-container your-class">` ***`your-class`***

You can add several sliders to the page, but you need to add different classes to them ***`your-class-1`*** ***`your-class-2`***
```
  <div class="slider-container your-class">

    <div class="slider">
  
      <div class="slider__item">
        <img src="https://i.ibb.co/S6z8yfv/1.jpg" alt="">
      </div>
      <div class="slider__item">
        <img src="https://i.ibb.co/yg4sRTx/2.jpg" alt="">
      </div>
      <div class="slider__item">
        <img src="https://i.ibb.co/sbv51xk/3.jpg" alt="">
      </div>
      <div class="slider__item">
        <img src="https://i.ibb.co/L64DScb/4.jpg" alt="">
      </div>
  
    </div>
  
    <div class="arrows">
      <span class="arrows__item arrows__item_prew">&#10096;</span>
      <span class="arrows__item arrows__item_next">&#10097;</span>
    </div>
  
  </div>
```

## Initialization ##
```
 slider({
   name: ".your-class",
});
```
## Initialization with parameters ##
```
slider({
   name: ".your-class",
   dots: true,
   numberSlid: true,
   line: true
});
```
## Settings ##
>### `name: ".your-class"` ###
>>Slider initialization
>### `dots: true` ###
>>Show dots
>### `numberSlid: true` ###
>>Show slide counter
>### `line: true` ###
>>Show progress line
