
<div align="center">
<h1>Buttons.css</h1>
<p>Simple CSS for buttons and dropdowns.</p>
<img src="https://img.shields.io/badge/version-1.0.2-green.svg">
<img src="https://img.shields.io/github/issues/gustavoquinalha/buttons-css.svg">
<img src="https://img.shields.io/github/license/gustavoquinalha/buttons-css.svg">
</div>

# Demos
- [Online Demo](http://quinalha.me/buttons-css/)
- [Documentation](http://quinalha.me/buttons-css/#install)
- [Codepen Demo](https://codepen.io/gustavoquinalha/pen/paaKxq?editors=1100)
- [Playground](http://quinalha.me/playground-buttons-css/)

# Install
```
$ npm i @gustavoquinalha/buttons-css -D
```
```
$ yarn add @gustavoquinalha/buttons-css -D
```
or
```
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@gustavoquinalha/buttons-css@1.0.1/assets/css/buttons.min.css">
```

# Docs
### Default
```html
<button type="button" name="button" class="btn">Default</button>
<a href="#" class="btn">Default Link</a>
```
### Sizes
```html
<button type="button" name="button" class="btn btn-lg">Button Large</button>
<button type="button" name="button" class="btn">Button Normal</button>
<button type="button" name="button" class="btn btn-sm">Button Small</button>
```
### Full width
```html
<button type="button" name="button" class="btn btn-full">Full width</button>
```
### Rounded
```html
<button type="button" name="button" class="btn btn-rounded">Rounded</button>
<a href="#" class="btn btn-rounded">Link Rounded</a>
```
### Primary colors
```html
<button type="button" name="button" class="btn btn-primary">Button primary</button>
<button type="button" name="button" class="btn btn-secundary">Button secundary</button>
```
### Status
```html
<button type="button" name="button" class="btn btn-warning">Warning</button>
<button type="button" name="button" class="btn btn-danger">Danger</button>
<button type="button" name="button" class="btn btn-success">Success</button>
```
### Disabled
```html
<button type="button" name="button" class="btn" disabled>Disabled</button>
<button type="button" name="button" class="btn btn-primary disabled">Disabled</button>
```
### Buttons + icons
```html
<button type="button" name="button" class="btn"><span class="feather-icon icon-arrow-left icon-margin-right"></span> Previous</button>
<button type="button" name="button" class="btn"><span class="feather-icon icon-pause"></span></button>
<button type="button" name="button" class="btn"><span class="feather-icon icon-play"></span></button>
<button type="button" name="button" class="btn">Next <span class="feather-icon icon-arrow-right icon-margin-left"></span></button>
```
### Icons
```html
<button type="button" name="button" class="btn btn-link"><span class="feather-icon icon-x"></span></button>
<button type="button" name="button" class="btn btn-link"><span class="feather-icon icon-book"></span></button>
<button type="button" name="button" class="btn btn-link"><span class="feather-icon icon-camera"></span></button>
<button type="button" name="button" class="btn btn-link"><span class="feather-icon icon-file"></span></button>>
```
### Transparent background
```html
<button type="button" name="button" class="btn btn-link btn-transparent"><span class="feather-icon icon-chevrons-left"></span></button>
<button type="button" name="button" class="btn btn-link btn-transparent"><span class="feather-icon icon-chevrons-right"></span></button>
<button type="button" name="button" class="btn btn-link btn-transparent"><span class="feather-icon icon-edit"></span></button>
<button type="button" name="button" class="btn btn-link btn-transparent"><span class="feather-icon icon-x"></span></button>
```
### Loading
```html
<button type="button" name="button" class="btn btn-min-width btn-link"><span class="feather-icon icon-loader"></span></button>
<button type="button" name="button" class="btn btn-min-width btn-link">Loading<span class="feather-icon icon-loader icon-margin-left"></button>
```
### Group buttons
```html
<div class="group-buttons">
  <button type="button" name="button" class="btn btn-active">Group 1</button>
  <button type="button" name="button" class="btn">Group 2</button>
  <button type="button" name="button" class="btn">Group 3</button>
  <button type="button" name="button" class="btn">Group 4</button>
</div>

<div class="group-buttons column" style="max-width: 300px">
  <button type="button" name="button" class="btn">Group 1</button>
  <button type="button" name="button" class="btn">Group 2</button>
  <button type="button" name="button" class="btn">Group 3</button>
  <button type="button" name="button" class="btn">Group 4</button>
</div>
```
### Dropdowns
```html
<div class="example-button container wrap container wrap">
<div class="dropdown margin-bottom-10" style="width: 300px;">
  <button type="button" name="button" class="btn">Dropdown <span class="feather-icon icon-margin-left icon-chevron-down"></span></button>
  <div class="dropdown-content">
    <ul>
      <li>
        <a href="#">
        Edit
      </a>
      </li>
      <li>
        <a href="#">
        Print
      </a>
      </li>
      <li>
        <a href="#">
        Delete
      </a>
      </li>
    </ul>
  </div>
</div>
```
### Badges
```html
<div class="badge">
  <div class="badge--number">0.0.1</div>
  <a href="#" class="btn">Version</a>
</div>

<div class="badge">
  <div class="badge--number">3</div>
  <a href="#" class="btn btn-secundary"><span class="feather-icon icon-star icon-margin-right"></span> Stars</a>
</div>

<div class="badge">
  <div class="badge--number">6</div>
  <a href="#" class="btn btn-danger"><span class="feather-icon icon-alert-triangle icon-margin-right"></span> Issues</a>
</div>
```
