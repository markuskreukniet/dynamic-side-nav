[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/MCKreukniet/dynamic-side-nav)

# \<dynamic-side-nav\>

The web component `dynamic-side-nav` is a button. When a user touches the button, a side navigation wil open. The content in the side navigation determines the width of the navigation.

## Installation

```
bower install --save MCKreukniet/dynamic-side-nav
```

## Example

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="dynamic-side-nav.html">
    <style>
      dynamic-side-nav {
        height: 21rem;
      }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<dynamic-side-nav>

  <ul style="list-style-type: none; padding: 0; margin: 3rem;">
    <li style="margin-bottom: 1rem;">nav item 1</li>
    <li style="margin-bottom: 1rem;">nav item 2</li>
    <li style="margin-bottom: 1rem;">nav item 3</li>
    <li>nav item 4</li>
  </ul>

</dynamic-side-nav>
```

## API Reference
### Properties
**image-open** : string  
Change the image in the open button, which is the button that can open the side navigation. The string value is used in the `src` attribute of the image.

**image-close** : string  
Change the image in the button, which can be visible when the side navigation is open. The string value is used in the `src` attribute of the image.

**side** : string = left  
Choose which side the side navigation opens. Possible values are: `left` and `right`.

## Styling

| Custom property              | Description | Default |
| ---------------------------- | ----------- | ------- |
| `--img-open-width`           | `width` of the image in the open button | `2rem` |
| `--img-open-height`          | `height` of the image in the open button | `2rem` |
| `--img-close-width`          | `width` of the image in the close button | `2rem` |
| `--img-close-height`         | `height` of the image in the close button | `2rem` |
| `--img-open-color`           | `stroke` of the default SVG image in the open button | `rgba(0, 0, 0, 0.87)` |
| `--img-open-linecap`         | `stroke-linecap` of the default SVG image in the open button. Suggested values: `round`, `square` | `square` |
| `--img-close-color`          | `stroke` of the default SVG image in the close button | `rgba(0, 0, 0, 0.87)` |
| `--img-close-linecap`        | `stroke-linecap` of the default SVG image in the close button. Suggested values: `round`, `square` | `square` |
| `--content-min-width`        | `min-width` of the content container | `1rem` |
| `--content-max-width`        | `max-width` of the content container | `initial` |
| `--content-background-color` | `background-color` of the content container | `#fff` |
| `--content-box-shadow`       | `box-shadow` of the content container | `0 0 1.84615384615rem 0.30769230769rem rgba(0, 0, 0, 0.4)` |
| `--overlay-background-color` | `background-color` of the overlay | `rgba(0, 0, 0, 0.4)` |
| `--side-nav-z-index`         | `z-index` of the content container and the overlay | `0` |

## License

[Apache License 2.0](https://github.com/MCKreukniet/dynamic-side-nav/blob/master/LICENSE.md)
