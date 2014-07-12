##FlexibleCarousel
================

Super flexible light carousel plugin

[Demo](http://codepen.io/anilkabobo/pen/cvdmF/)

###HTML template you can use:

```
<div class="carousel-wrapper" id="products">
  <ul class="carousel-inner clearfix">
      <li class="item">
          <p class="item-info">Lorem ipsum</p>
      </li>
      <li class="item">
          <p class="item-info">Lorem ipsum</p>
      </li>
  </ul>
  <a href="#" class="carousel-left"></a>
  <a href="#" class="carousel-right"></a>
</div>
```

1. `.carousel-wrapper` - Element for wrapping list with carousel items and navigation buttons.
2. `.carousel-inner` - List with items.
3. `.item` - Class for items.
4. `.carousel-left` and `.carousel-right` - Left and right buttons for navigation.


###Creating carousel in JavaScript:

```
//Initializing carousel
if (document.getElementById('products')) {
  var productsCarousel = new Carousel('products', 3);
}
```

1. `'products'` - Id of wrapper element.
2. `3` - number of visible items.
3. `if (document.getElementById('products'))` - checking if such element exist.


###CSS

You can delete demo styles which placed under `/*Demo styles*/` comment and style carousel yourself.
