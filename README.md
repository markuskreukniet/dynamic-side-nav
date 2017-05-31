[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/MCKreukniet/dynamic-side-nav)

# \<dynamic-side-nav\>

Thee web component `dynamic-side-nav` is a button. When a user touches the button, a side navigation wil open. The content in the side navigation determines the width of the navigation.

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

## License

[Apache License 2.0](https://github.com/MCKreukniet/dynamic-side-nav/blob/master/LICENSE.md)
