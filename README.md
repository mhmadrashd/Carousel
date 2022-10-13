# Custom Carousel

[Demo Live Link](https://mhmadrashd.github.io/Carousel/)

## - To use it add this files to your project:

### - js carousel file

### - carousel.scss file

### - in html file write this code:

```
<div class="carousel">
  <div class="items">

    <div class="item">
      <h1>item 1</h1>
    </div>

    <div class="item">
      <h1>item 2</h1>
    </div>

  </div>
</div>
```

### - To display control buttons:

```
<div class="carousel">
  <button class="last-button"><i class="fa-fw fa-solid fa-chevron-left"></i></button>

  <div class="items">

    <div class="item">
      <h1>item 1</h1>
    </div>

    <div class="item">
      <h1>item 2</h1>
    </div>

  </div>

  <button class="next-button"><i class="fa-fw fa-solid fa-chevron-right"></i></button>
</div>
```

## You can customize everything in a carousel like:

### - Width

```
  <div class="items" width="200px">
  </div>
```

### - Height

```
  <div class="items" height="300px">
  </div>
```

### - Loop

```
  <div class="items" loop="true">
  </div>
```

### - Auto loop

```
  <div class="items" auto-loop="true">
  </div>
```

### - Loop interval

```
  <div class="items" interval="2000">
  </div>
```

### - Displayed item number

```
  <div class="items" show-item="3">
  </div>
```

### - Show/hide scroll bar

```
  <div class="items" scroll="true">
  </div>
```

### - Customize navigation buttons anywhere you want (top, bottom, left and right).

```
<div class="carousel">

  <button class="last-button"><i class="fa-fw fa-solid fa-chevron-left"></i></button>
  <button class="next-button"><i class="fa-fw fa-solid fa-chevron-right"></i></button>

  <div class="items">

  </div>

</div>
```

### - You can also seperate button in right and other button in left or top and bottom.

```
<div class="carousel">
  <button class="last-button"><i class="fa-fw fa-solid fa-chevron-left"></i></button>

  <div class="items">
  </div>

  <button class="next-button"><i class="fa-fw fa-solid fa-chevron-right"></i></button>
</div>
```

## Built With

- HTML5
- SCSS
- JavaScript
