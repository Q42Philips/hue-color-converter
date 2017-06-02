# Hue color converter
[![npm version](https://badge.fury.io/js/%40q42philips%2Fhue-color-converter.svg)](https://badge.fury.io/js/%40q42philips%2Fhue-color-converter)
[![Build Status](https://travis-ci.org/Q42Philips/hue-color-converter.svg?branch=master)](https://travis-ci.org/Q42Philips/hue-color-converter)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)

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