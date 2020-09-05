<p align="center">
  <a href='https://www.npmjs.com/package/@yaireo/dragsort'>
      <img src="https://img.shields.io/npm/v/@yaireo/dragsort.svg" />
  </a>
  <a href='https://simple.wikipedia.org/wiki/MIT_License'>
      <img src="https://img.shields.io/badge/license-MIT-lightgrey" />
  </a>
  <img src="https://img.shields.io/bundlephobia/minzip/@yaireo/dragsort" />
  <img src="https://img.shields.io/npm/dw/@yaireo/dragsort" />
</p>

[dragSort](https://codepen.io/vsync/pen/3f6b998fa1bb1b7c7f74ec89152f39f9/?editors=0100) - lightweight HTML5 drag-&-drop sorting
========

<a align="center" href="https://codepen.io/vsync/pen/3f6b998fa1bb1b7c7f74ec89152f39f9/?editors=0100">

![drag-sort demo](https://raw.githubusercontent.com/yairEO/dragsort/master/demo.gif)

</a>

## Installation
```sh
    npm i @yaireo/dragsort --save
```

## Usage

#### HTML
```html
<ul class="list">
    <li>A</li>
    <li>BBBBB</li>
    <li>CCCCCCCCC</li>
    <li>DDDD DDDDDDDD</li>
    <li>EE</li>
</ul>
```

#### javascript
```js
    var listElm = document.querySelector('.list'),
        dragSort = new DragSort(listElm);
```

## Pre-setup suggestions:

* Setting `box-sizing: border-box` on your list's children is a good idea
* Should include the `dragsort.css` file (from this repository)
