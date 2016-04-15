# ti-fontawesome
Fontawesome for Appcelerator (Titanium) Mobile

## Description

This is made to have a mapping between the Fontawesome CSS classes and the unicode characters to be usable.

There is also a sample functionality to create a `Ti.UI.createLabel()` with the icon as text.
Labels can be added to almost any other Ti element.

Fontawesome `4.5` is currently supported.

## Usage

### Copy the font file
Copy the `fontawesome-webfont.ttf` file to `/Resources/fonts/`

### Include the module via
```JS
var fontAwesome = require('/ui/fontAwesome');
fa = new fontAwesome();

var label = fa.createLabel({
	icon: 'fa-fort-awesome'
});
```
