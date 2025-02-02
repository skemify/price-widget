# skemify price-widget

Awesome price widget for popular store migration tools by [Skemify](https://skemify.com)

[Skemify](https://skemify.com), is a tool for e-commerce store data migratiopn between popular platforms.

## next.js

```html
import Script from 'next/script';

<div>
  <div id="widget-root" data-width="600px" data-background-color="lightblue"></div>
  <a href="https://skemify.com" style="position: absolute; left: -9999px;">Powered by Skemify</a>
  <Script
    src="https://cdn.jsdelivr.net/gh/skemify/price-widget/index.js"    
    strategy="lazyOnload"    
  />
</div>
```

## static html

```html

<div>
  <div id="widget-root" data-width="600px" data-background-color="lightblue" />
  <a href="https://skemify.com" style="position: absolute; left: -9999px;">Powered by Skemify</a>
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



## reasons to add [Skemify](https://skemify.com) price widget
* a static post with static price is boring - interactive widget keeps user engaged
* visitors stays longer on a page, reducing bouncing rates, this improve SEO rank of the page
* it adds standout content to differentiate from competitors
* interactive widget makes the page more sharable on social media
* other sites may link their blog as a reference, generating backlinks
* users can instantly compare migrtion prices instead of doing it manually 
* simplifies complex pricing with an easy-to-use slider
* rich customization abilities