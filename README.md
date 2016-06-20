# XING CSS Icons

**XING icons** build just with CSS.

To put a link to your XING profile on your website using an icon, you could use an image or to save an http 
request you can replace the image with some HTML and CSS. So, here you will find the HTML and CSS for different XING 
icons.

### [Demo](https://fabianmebus.com/xing-css-icons/)

## How to Use It

There is one CSS file for each icon variation. Check out the markup below and copy the CSS code of the icon you prefer into your 
CSS.

### Inline

To place the icon inline with a `span` element, use the following markup:

```html
<span class="icon-xing">
  <a href="XING_PROFILE_URL" target="_blank" rel="me" aria-label="XING profile"></a>
</span>
<!-- or for the light variation  -->
<span class="icon-xing-light">
  <a href="XING_PROFILE_URL" target="_blank" rel="me" aria-label="XING profile"></a>
</span>
```

### Lists

To place the icon in a list element, use the following markup:

```html
<ul>
  <li class="icon-xing">
    <a href="XING_PROFILE_URL" target="_blank" rel="me" aria-label="XING profile"></a>
  </li>
  <!-- or for the light variation  -->
  <li class="icon-xing-light">
    <a href="XING_PROFILE_URL" target="_blank" rel="me" aria-label="XING profile"></a>
  </li>

</ul>
```

## Browser Support
The CSS3 property `transform` and the transform-function `skewX()` are the key to render the icons. 
[Here](http://caniuse.com/#search=transform) you will find the support for the `transform` property.

## Known Issues
There are problems with the precise rendering when certain font sizes are applied. This is caused by rounding issues.

## License
It's all yours under [MIT](LICENSE.md).
