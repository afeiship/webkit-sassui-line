# wsui-layout-fixed-sidebar
> Sassui for layout fixed sidebar.

[![version][version-image]][version-url]
[![license][license-image]][license-url]
[![size][size-image]][size-url]
[![download][download-image]][download-url]

## installation
```shell
npm i @jswork/wsui-layout-fixed-sidebar
```

## usage
```scss
// use sass
@import '~@jswork/wsui-layout-fixed-sidebar/dist/index.scss';
// use css
@import '~@jswork/wsui-layout-fixed-sidebar/dist/style.css';


// generate your styles
.test-wsui-layout-fixed-sidebar {
  @include wsui-layout-fixed-sidebar(250px);
  height: 400px;
  background: #eee;
  .is-sidebar,
  .is-main {
    height: 400px;
  }

  > .is-sidebar {
    background: lightgreen;
  }
  > .is-main {
    background: orange;
  }
}
```

```html
<div class="test-wsui-layout-fixed-sidebar is-container" data-placement="left">
  <aside class="is-sidebar">Sidebar</aside>
  <div class="is-main">main</div>
</div>
```

## preview
- https://afeiship.github.io/wsui-layout-fixed-sidebar/

## license
Code released under [the MIT license](https://github.com/afeiship/wsui-layout-fixed-sidebar/blob/master/LICENSE.txt).

[version-image]: https://img.shields.io/npm/v/@jswork/wsui-layout-fixed-sidebar
[version-url]: https://npmjs.org/package/@jswork/wsui-layout-fixed-sidebar

[license-image]: https://img.shields.io/npm/l/@jswork/wsui-layout-fixed-sidebar
[license-url]: https://github.com/afeiship/wsui-layout-fixed-sidebar/blob/master/LICENSE.txt

[size-image]: https://img.shields.io/bundlephobia/minzip/@jswork/wsui-layout-fixed-sidebar
[size-url]: https://github.com/afeiship/wsui-layout-fixed-sidebar/blob/master/dist/wsui-layout-fixed-sidebar.min.js

[download-image]: https://img.shields.io/npm/dm/@jswork/wsui-layout-fixed-sidebar
[download-url]: https://www.npmjs.com/package/@jswork/wsui-layout-fixed-sidebar

