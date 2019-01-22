## Tooltip

Simple tooltip.

## Installation

```
npm install --save css-ui-tooltip
```

## Demo

- https://css-ui.github.io/tooltip

## Quick start

CSS dependencies.

```html
<link rel="stylesheet" href="path/to/normalize.css">
<link rel="stylesheet" href="path/to/open-sans.css">
<link rel="stylesheet" href="path/to/cssui.css">
```

CSS tooltip style.

```html
<link rel="stylesheet" href="path/to/style.tooltip.css">
```

CSS tooltip theme.

```html
<link rel="stylesheet" href="path/to/style.tooltip.theme.css">
```

Set font.

```html
<style>
	body {
		font-family: 'Open Sans', sans-serif;
	}
</style>

Simple tooltip html.

```html
<!-- primary color -->
<span class="tooltip">Top <span class="primary top">Top</span></span>
<span class="tooltip">Bottom <span class="primary bottom">Bottom</span></span>
<span class="tooltip">Left <span class="primary left">Left</span></span>
<span class="tooltip">Right <span class="primary right">Right</span></span>

<!-- common color -->
<span class="tooltip">Top <span class="common top">Top</span></span>
<span class="tooltip">Bottom <span class="common bottom">Bottom</span></span>
<span class="tooltip">Left <span class="common left">Left</span></span>
<span class="tooltip">Right <span class="common right">Right</span></span>

<!-- success color -->
<span class="tooltip">Top <span class="success top">Top</span></span>
<span class="tooltip">Bottom <span class="success bottom">Bottom</span></span>
<span class="tooltip">Left <span class="success left">Left</span></span>
<span class="tooltip">Right <span class="success right">Right</span></span>

<!-- warning color -->
<span class="tooltip">Top <span class="warning top">Top</span></span>
<span class="tooltip">Bottom <span class="warning bottom">Bottom</span></span>
<span class="tooltip">Left <span class="warning left">Left</span></span>
<span class="tooltip">Right <span class="warning right">Right</span></span>

<!-- danger color -->
<span class="tooltip">Top <span class="danger top">Top</span></span>
<span class="tooltip">Bottom <span class="danger bottom">Bottom</span></span>
<span class="tooltip">Left <span class="danger left">Left</span></span>
<span class="tooltip">Right <span class="danger right">Right</span></span>
```

Enjoy tooltip.
