# Micro Responsive Grid
A super light responsive CSS grid system for Mobile, Tablet and Desktop. No real reason for making another one other than wanting the syntax of the Foundation grid system, without all the bloat. Syntax is based on the Foundation 5 grid system. Live demo avalible at (http://foxx.io/responsive/)

## Grid Syntax
```html
<div class="row">
	<div class="large-3 medium-6 mobile-4 columns">
	</div>
</div>
```

## Visibility Syntax
Visibility works on level-and-lower basis e.g. show-medium will be visible on medium and lower and hide-medium will be hidden on medium and lower.

```html
<div class="row">
	<div class="large-12 hide-large"></div>
	<div class="large-12 hide-medium"></div>
	<div class="large-12 hide-small"></div>
</div>
<div class="row">
	<div class="large-12"></div>
	<div class="large-12 show-medium"></div>
	<div class="large-12 show-small"></div>
</div>
```

## Browser Support

Supports IE8 with 'repond.js' and all other modern browsers.