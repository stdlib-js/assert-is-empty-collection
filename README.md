<!--

@license Apache-2.0

Copyright (c) 2021 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->

# isEmptyCollection

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Test if a value is an empty collection.

<section class="installation">

## Installation

```bash
npm install @stdlib/assert-is-empty-collection
```

</section>

<section class="usage">

## Usage

```javascript
var isEmptyCollection = require( '@stdlib/assert-is-empty-collection' );
```

#### isEmptyCollection( value )

Tests if a value is an empty `collection`.

```javascript
var bool = isEmptyCollection( [] );
// returns true
```

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- eslint-disable object-curly-newline, no-array-constructor -->

<!-- eslint no-undef: "error" -->

```javascript
var Int8Array = require( '@stdlib/array-int8' );
var Uint8Array = require( '@stdlib/array-uint8' );
var Uint8ClampedArray = require( '@stdlib/array-uint8c' );
var Int16Array = require( '@stdlib/array-int16' );
var Uint16Array = require( '@stdlib/array-uint16' );
var Int32Array = require( '@stdlib/array-int32' );
var Uint32Array = require( '@stdlib/array-uint32' );
var Float32Array = require( '@stdlib/array-float32' );
var Float64Array = require( '@stdlib/array-float64' );
var isEmptyCollection = require( '@stdlib/assert-is-empty-collection' );

var bool = isEmptyCollection( [] );
// returns true

bool = isEmptyCollection( new Float64Array( 0 ) );
// returns true

bool = isEmptyCollection( new Float32Array( 0 ) );
// returns true

bool = isEmptyCollection( new Int32Array( 0 ) );
// returns true

bool = isEmptyCollection( new Uint32Array( 0 ) );
// returns true

bool = isEmptyCollection( new Int16Array( 0 ) );
// returns true

bool = isEmptyCollection( new Uint16Array( 0 ) );
// returns true

bool = isEmptyCollection( new Int8Array( 0 ) );
// returns true

bool = isEmptyCollection( new Uint8Array( 0 ) );
// returns true

bool = isEmptyCollection( new Uint8ClampedArray( 0 ) );
// returns true

bool = isEmptyCollection( { 'length': 0 } );
// returns true

bool = isEmptyCollection( new Array() );
// returns true

bool = isEmptyCollection( [ 1, 2, 3, 4 ] );
// returns false

bool = isEmptyCollection( {} );
// returns false
```

</section>

<!-- /.examples -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2021. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/assert-is-empty-collection.svg
[npm-url]: https://npmjs.org/package/@stdlib/assert-is-empty-collection

[test-image]: https://github.com/stdlib-js/assert-is-empty-collection/actions/workflows/test.yml/badge.svg
[test-url]: https://github.com/stdlib-js/assert-is-empty-collection/actions/workflows/test.yml

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/assert-is-empty-collection/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/assert-is-empty-collection?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/assert-is-empty-collection.svg
[dependencies-url]: https://david-dm.org/stdlib-js/assert-is-empty-collection/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/assert-is-empty-collection/main/LICENSE

<!-- <related-links> -->

<!-- </related-links> -->

</section>

<!-- /.links -->
