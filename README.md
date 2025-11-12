# [material-icons](https://coscomui-doku.coscom.de/icons) [![Downloads](https://img.shields.io/npm/dm/material-icons)](https://www.npmjs.com/package/@coscom/material-icons)

Latest icon fonts and CSS for self-hosting material design icons.

> This package is automatically updated, so it will always have the latest icons from Google.


- [Installation](#installation)
- [Usage](#usage)
- [Available Icons](#available-icons)

## Installation

Install the [latest version][releases] using:

```sh
npm install @coscom/material-icons@latest
```

## Usage

Import in JS (example: `src/index.js` in Vue App, `src/main.js` in Vue CLI):

```js
import '@coscom/material-icons/iconfont/outlined.css';
```

or import in CSS (example: `src/styles.css` in Vue CLI):

```css
@import '@coscom/material-icons/iconfont/outlined.css';
```

or import in HTML:

```html
<link href="/path/to/material-icons/iconfont/outlined.css" rel="stylesheet">
```

To display an icon, use one of the following:

```html
<span class="material-icons-outlined">account_circle</span>
<span class="material-icons-outlined">alarm</span>
<span class="material-icons-outlined">block</span>
<span class="material-icons-outlined">color_lens</span>
```

### Using Sass

Import in Sass (example: `src/styles.scss` in Vue CLI):

```scss
@import '@coscom/material-icons/iconfont/outlined.scss';
```

Available Sass variables:

```scss
$material-icons-font-path: './' !default;
$material-icons-font-size: 24px !default;
$material-icons-font-display: block !default;
```

If you are getting errors with webpack or Vue CLI, add this line before importing:

```scss
$material-icons-font-path: '~material-icons/iconfont/';
```

## Available Icons

See [demo].

## License

Material design icons are created by [Google](https://github.com/google/material-design-icons#license).

> We have made these icons available for you to incorporate into your products under the [Apache License Version 2.0][license]. Feel free to remix and re-share these icons and documentation in your products.
We'd love attribution in your app's *about* screen, but it's not required.

[demo]: https://coscomui-doku.coscom.de/icons
