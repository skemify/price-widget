# skemify price-widget

Awesome price widget for popular store migration tools by Skemify

Skemify, is a tool for e-commerce store data migratiopn between popular platforms.

## next.js

```html
import Script from 'next/script';

<div>
  <div id="widget-root" data-width="600px" data-background-color="lightblue"></div>
  <Script
    src="https://cdn.jsdelivr.net/gh/skemify/price-widget/index.js"    
    strategy="lazyOnload"    
  />
</div>
```

## static html

```html

<div>
  <div id="widget-root" data-width="600px" data-background-color="lightblue"></div>
  <script src="https://cdn.jsdelivr.net/gh/skemify/price-widget/index.js"
  />
</div>
```


## properties

* `data-width` - set widget width, default `600px`
* `data-background-color` - set background color, default `#f9f9f9`
* `data-bar-color` - color of bars, default `#ffcc00`
* `data-text-color` - color of texts, default `#000000`
* `data-set` - array of migration services, default `le, c2c, mp, sk`, full set is `le, c2c, mp, sk, nc` for `litextension`, `cart2cart`, `migrationpro`, `skemify` and `next-cart`

## screenshot
![alt](https://cdn.jsdelivr.net/gh/skemify/price-widget/assets/screenshot.png)