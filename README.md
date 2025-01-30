# price-widget

Awesome price widget for popular store migration tools by Skemify

Skemify, is a tool for e-commerce store data migratiopn between popular platforms.

## next.js

```html
import Script from 'next/script';

<div>
  <div id="widget-root"></div>
  <Script
    src="https://cdn.jsdelivr.net/gh/skemify/price-widget/index.js"
    strategy="lazyOnload"
  />
</div>
```

## static html

```html

<div>
  <div id="widget-root"></div>
  <script
    src="https://cdn.jsdelivr.net/gh/skemify/price-widget/index.js"
    strategy="lazyOnload"
  />
</div>
```