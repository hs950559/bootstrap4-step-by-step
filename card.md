# Card

```
// wrapper class
.card

// regular content classes inside .card
.card-title
.card-text
.card-blockquote
.card-link

// card Images
.card-img
.card-img-top
.card-img-bottom

// Specials sections inside .card
.card-header
.card-footer
.card-block
.card-img-overlay

// List inside card
ul.list-group.list-group-flush
li.list-group-item

// Card styles on .card
.card-primary
.card-inverse
.card-success
.card-info
.card-warning
.card-danger
```

## Card Layout

card with unequal height, no gutter 

```html
<div class="card-group">
	<div class="card"></div>
	<div class="card"></div>
	<div class="card"></div>
</div>
```

card with gutter, equal height

```html
<div class="card-deck-wrapper">
	<div class="card-deck">
		<div class="card"></div>
		<div class="card"></div>
		<div class="card"></div>
	</div>	
</div>
```

card with un-equal height, with gutter ( nicely adjust and fits with other cards)

```html
<div class="card-columns">
	<div class="card"></div>
	<div class="card"></div>
	<div class="card"></div>
</div>
```