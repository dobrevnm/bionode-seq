![bionode logo](https://raw.github.com/bionode/bionode/master/docs/bionode-logo.min.svg "bionode")
# bionode [![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Coveralls Status][coveralls-image]][coveralls-url] [![Dependency Status](https://david-dm.org/bionode/bionode.png?theme=shields.io)](https://david-dm.org/bionode/bionode)

> A Node.js JavaScript library for client and server side bioinformatics.

Install
-------

Install bionode with [npm](https://npmjs.org/):

```sh
$ npm install bionode
```

You can also install it for client side with [bower](http://bower.io)

```sh
$ bower install bionode
```

Alternatively, just include `bionode.min.js` via a `<script/>` in your page.


Usage
-----

If you're using bionode with Node.js, you can require the module:

```js
var bionode = require('bionode')
```

In-browser, `bionode` is available as a global variable.

Please read the [documentation](https://rawgithub.com/bionode/bionode/master/docs/bionode.html) for the methods exposed by bionode.


Contributing
------------

To contribute to bionode, clone this repo locally and commit your code on a separate branch.

Please write unit tests for your code, and check that everything works by running the following before opening a pull-request:

```sh
$ npm test
```

Please also check for code coverage:

```sh
$ npm run coverage
```

To rebuild and minify the module for the browser:

```sh
$ npm run build-browser
```

To rebuild the documentation using the comments in the code:

```sh
$ npm run build-docs
```

License
-------

bionode is licensed under the [MIT](https://raw.github.com/bionode/bionode/master/LICENSE) license.

[npm-url]: https://npmjs.org/package/bionode
[npm-image]: https://badge.fury.io/js/bionode.png
[travis-url]: https://travis-ci.org/bionode/bionode
[travis-image]: https://travis-ci.org/bionode/bionode.png?branch=master
[coveralls-url]: https://coveralls.io/r/bionode/bionode
[coveralls-image]: https://coveralls.io/repos/bionode/bionode/badge.png
[depstat-url]: https://david-dm.org/bionode/bionode
[depstat-image]: https://david-dm.org/bionode/bionode.png
