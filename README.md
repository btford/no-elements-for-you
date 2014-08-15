# no elements for you [![Build Status](https://travis-ci.org/btford/no-elements-for-you.svg)](https://travis-ci.org/angular/btford/no-elements-for-you.js)

Instrument code and throw if it ever touches an Element

## Install

```shell
$ npm install no-elements-for-you
```

## Use

```javascript
var nope = require('no-elements-for-you');

var niceTry = nope(function () {
  return document.getElementsByTagName('body');
});

niceTry();
// -> throws
```

## License
MIT
