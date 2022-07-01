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



<section class="usage">

## Usage

```javascript
import isEmptyCollection from 'https://cdn.jsdelivr.net/gh/stdlib-js/assert-is-empty-collection@esm/index.mjs';
```

#### isEmptyCollection( value )

Tests if a value is an empty collection.

```javascript
var bool = isEmptyCollection( [] );
// returns true
```

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- eslint-disable object-curly-newline -->

<!-- eslint no-undef: "error" -->

```html
<!DOCTYPE html>
<html lang="en">
<body>
<script type="module">

import Int8Array from 'https://cdn.jsdelivr.net/gh/stdlib-js/array-int8@esm/index.mjs';
import Uint8Array from 'https://cdn.jsdelivr.net/gh/stdlib-js/array-uint8@esm/index.mjs';
import Uint8ClampedArray from 'https://cdn.jsdelivr.net/gh/stdlib-js/array-uint8c@esm/index.mjs';
import Int16Array from 'https://cdn.jsdelivr.net/gh/stdlib-js/array-int16@esm/index.mjs';
import Uint16Array from 'https://cdn.jsdelivr.net/gh/stdlib-js/array-uint16@esm/index.mjs';
import Int32Array from 'https://cdn.jsdelivr.net/gh/stdlib-js/array-int32@esm/index.mjs';
import Uint32Array from 'https://cdn.jsdelivr.net/gh/stdlib-js/array-uint32@esm/index.mjs';
import Float32Array from 'https://cdn.jsdelivr.net/gh/stdlib-js/array-float32@esm/index.mjs';
import Float64Array from 'https://cdn.jsdelivr.net/gh/stdlib-js/array-float64@esm/index.mjs';
import isEmptyCollection from 'https://cdn.jsdelivr.net/gh/stdlib-js/assert-is-empty-collection@esm/index.mjs';

var bool = isEmptyCollection( [] );
// returns true

bool = isEmptyCollection( new Float64Array( [] ) );
// returns true

bool = isEmptyCollection( new Float32Array( [] ) );
// returns true

bool = isEmptyCollection( new Int32Array( [] ) );
// returns true

bool = isEmptyCollection( new Uint32Array( [] ) );
// returns true

bool = isEmptyCollection( new Int16Array( [] ) );
// returns true

bool = isEmptyCollection( new Uint16Array( [] ) );
// returns true

bool = isEmptyCollection( new Int8Array( [] ) );
// returns true

bool = isEmptyCollection( new Uint8Array( [] ) );
// returns true

bool = isEmptyCollection( new Uint8ClampedArray( [] ) );
// returns true

bool = isEmptyCollection( { 'length': 0 } );
// returns true

bool = isEmptyCollection( [ 1, 2, 3, 4 ] );
// returns false

bool = isEmptyCollection( {} );
// returns false

</script>
</body>
</html>
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

This package is part of [stdlib][stdlib], a standard library with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2022. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/assert-is-empty-collection.svg
[npm-url]: https://npmjs.org/package/@stdlib/assert-is-empty-collection

[test-image]: https://github.com/stdlib-js/assert-is-empty-collection/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/assert-is-empty-collection/actions/workflows/test.yml?query=branch:main

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

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/assert-is-empty-collection/tree/deno
[umd-url]: https://github.com/stdlib-js/assert-is-empty-collection/tree/umd
[esm-url]: https://github.com/stdlib-js/assert-is-empty-collection/tree/esm
[branches-url]: https://github.com/stdlib-js/assert-is-empty-collection/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/assert-is-empty-collection/main/LICENSE

<!-- <related-links> -->

<!-- </related-links> -->

</section>

<!-- /.links -->