# jQuery textTile Toolbar

A jQuery plugin to attach a textTile toolbar to textareas.

This plugin is based on on Redmine reStructuredText Formatter
developed by William Melody
https://github.com/alphabetum/redmine_restructuredtext_formatter

Adapted as a jQuery plugin by Maurizio Manetti.

## Installation:

To be documented. 

## Usage:

Include files from the dist folder:

```html
<!-- Simple Tree core CSS file -->
<link rel="stylesheet" href="css/textileToolbar.css">

<!-- jQuery 1.9+ or Zepto.js 1.0+ -->
<script src="//ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>

<!-- Simple Tree core JS file -->
<script src="js/jquery.TextileToolbar.min.js"></script>
```

Toolbar initialization should be executed after document ready, for example:

```javascript
$(document).ready(function() {
  $('.mytextareas').textileToolbar();
});
```

Toolbar can be applied programmatically:

```javascript
$('#add_toolbar').on('click',function(){
	$('#firstText').textileToolbar();
});	
```

Toolbar can be removed:

```javascript
$('#destroy_toolbar').on('click',function(){
	$('#firstText').textileToolbar('destroy');
});	
```

Live demo and examples: coming soon 

## Alternatives:

To do

## TODO:

- Documentation
- Examples
- Todo list
