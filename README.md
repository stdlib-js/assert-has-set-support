<!--

@license Apache-2.0

Copyright (c) 2018 The Stdlib Authors.

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

# Set Support

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Detect native [`Set`][mdn-set] support.



<section class="usage">

## Usage

```javascript
import hasSetSupport from 'https://cdn.jsdelivr.net/gh/stdlib-js/assert-has-set-support@esm/index.mjs';
```

#### hasSetSupport()

Detects if a runtime environment supports ES2015 [`Set`][mdn-set].

```javascript
var bool = hasSetSupport();
// returns <boolean>
```

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- eslint no-undef: "error" -->

```html
<!DOCTYPE html>
<html lang="en">
<body>
<script type="module">

import hasSetSupport from 'https://cdn.jsdelivr.net/gh/stdlib-js/assert-has-set-support@esm/index.mjs';

var bool = hasSetSupport();
if ( bool ) {
    console.log( 'Environment has Set support.' );
} else {
    console.log( 'Environment lacks Set support.' );
}

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

Copyright &copy; 2016-2023. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/assert-has-set-support.svg
[npm-url]: https://npmjs.org/package/@stdlib/assert-has-set-support

[test-image]: https://github.com/stdlib-js/assert-has-set-support/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/assert-has-set-support/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/assert-has-set-support/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/assert-has-set-support?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/assert-has-set-support.svg
[dependencies-url]: https://david-dm.org/stdlib-js/assert-has-set-support/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[cli-section]: https://github.com/stdlib-js/assert-has-set-support#cli
[cli-url]: https://github.com/stdlib-js/assert-has-set-support/tree/cli
[@stdlib/assert-has-set-support]: https://github.com/stdlib-js/assert-has-set-support/tree/main

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/assert-has-set-support/tree/deno
[umd-url]: https://github.com/stdlib-js/assert-has-set-support/tree/umd
[esm-url]: https://github.com/stdlib-js/assert-has-set-support/tree/esm
[branches-url]: https://github.com/stdlib-js/assert-has-set-support/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/assert-has-set-support/main/LICENSE

[mdn-set]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set

</section>

<!-- /.links -->
