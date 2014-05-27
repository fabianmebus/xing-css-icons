# Xing CSS icons

Xing is a social network for business contacts. To put a link to your Xing profile on your website using an icon you could just use an image or
to save an http request you can replace the image with some HTML and CSS. So, here you will find the HTML and CSS for different Xing icons.

## How to use it

There is one CSS file for each icon. Check out the markup below and copy the CSS code of the icon you prefer into your CSS file.


| Xing icon | Xing icon light |
|:---:|:---:|
| ![Xing icon](icon-xing.png "Xing icon") | ![Xing icon light](icon-xing-light.png "Xing icon light") |
| [icon-xing.css](icon-xing.css) | [icon-xing-light.css](icon-xing-light.css) |
| `.icon-xing` | `.icon-xing-light` |

### Inline

To place the icon inline with a `span` element use the following markup:

```html
<span class="icon-xing">
  <a href="URL_TO_YOUR_XING_PROFILE" target="_blank" rel="me" title="XING_ICON_TITLE">
    <span class="screen-reader-only">SCREEN_READER_CONTENT</span>
  </a>
</span>
<span class="icon-xing-light">
  <a href="URL_TO_YOUR_XING_PROFILE" target="_blank" rel="me" title="XING_ICON_TITLE">
    <span class="screen-reader-only">SCREEN_READER_CONTENT</span>
  </a>
</span>
```

### Lists

To place the icon in an ordered `ol` or unordered list `ul` use the following markup, example for an unordered list:

```html
<ul class="list-unstyled">
  <li class="icon-xing">
    <a href="URL_TO_YOUR_XING_PROFILE" target="_blank" rel="me" title="XING_ICON_TITLE">
      <span class="screen-reader-only">SCREEN_READER_CONTENT</span>
    </a>
  </li>
  <li class="icon-xing-light">
    <a href="URL_TO_YOUR_XING_PROFILE" target="_blank" rel="me" title="XING_ICON_TITLE">
      <span class="screen-reader-only">SCREEN_READER_CONTENT</span>
    </a>
  </li>
</ul>
```

## Browser support

The CSS3 property `transform` and the transform-function `skewX()` are the key to render the icons.
[Here](http://caniuse.com/#search=transform) you will find the support for the `transform` property.

### Known Issues

* There are problems with the precise rendering in all browsers with certain font sizes.

## License

It's all yours under [MIT](https://github.com/fabianmebus/xing-css-icons/blob/master/LICENSE.md).
