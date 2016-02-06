# bilinear_interpolate 
[![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Dependency Status][daviddm-url]][daviddm-image] [![Coverage Status][coveralls-image]][coveralls-url]

The best module ever.


## Install

```bash
$ npm install --save bilinear-interpolate
```


## Usage

```javascript
var bilinearInterpolate = require('bilinear-interpolate');
var line = bilinearInterpolate([[4, 45.5], [5, 44.5]]); 
line(4.5); // 45.0
```

## License

Copyright (c) 2016 Grady Morgan. Licensed under the MIT license.



[npm-url]: https://npmjs.org/package/bilinear-interpolate
[npm-image]: https://badge.fury.io/js/bilinear-interpolate.svg
[travis-url]: https://travis-ci.org/gradymorgan/bilinear-interpolate
[travis-image]: https://travis-ci.org/gradymorgan/bilinear-interpolate.svg?branch=master
[daviddm-url]: https://david-dm.org/gradymorgan/bilinear-interpolate.svg?theme=shields.io
[daviddm-image]: https://david-dm.org/gradymorgan/bilinear-interpolate
