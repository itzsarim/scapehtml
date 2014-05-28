scapehtml
=========

basic node module that escapes and unescapes HTML entities

html entities supported '&' '"' '\' '>'


## Installation

  npm install scapehtml --save

## Usage

  var scapehtml = require('scapehtml')
      escape = scapehtml.escape,
      unescape = scapehtml.unescape;

  var html = 'Hello World',
      escaped = escape(html),
      unescaped = unescape(escaped);

  console.log('html', html, 'escaped', escaped, 'unescaped', unescaped);


## Contributing

In lieu of a formal styleguide, take care to maintain the existing coding style.
Add unit tests for any new or changed functionality. Lint and test your code.

## Release History

* 0.1.0 Initial release
