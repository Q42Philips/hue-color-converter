# Hue color converter
Convert RGB values to XY values.

## Getting started
Install using npm:
```
npm install --save @q42philips/hue-color-converter
```

Basic usage:
``` javascript
var converter = require('@q42philips/hue-color-converter');

// Using default color points
console.log(converter.calculateXY(255, 0, 0));
// prints [ 0.7006, 0.2993 ]

// Calculate for a specific bulb model
console.log(converter.calculateXY(255, 0, 0, 'LCT001');
// prints [ 0.7, 0.2986 ]
```