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


<details>
  <summary>
    About stdlib...
  </summary>
  <p>We believe in a future in which the web is a preferred environment for numerical computation. To help realize this future, we've built stdlib. stdlib is a standard library, with an emphasis on numerical and scientific computation, written in JavaScript (and C) for execution in browsers and in Node.js.</p>
  <p>The library is fully decomposable, being architected in such a way that you can swap out and mix and match APIs and functionality to cater to your exact preferences and use cases.</p>
  <p>When you use stdlib, you can be absolutely certain that you are using the most thorough, rigorous, well-written, studied, documented, tested, measured, and high-quality code out there.</p>
  <p>To join us in bringing numerical computing to the web, get started by checking us out on <a href="https://github.com/stdlib-js/stdlib">GitHub</a>, and please consider <a href="https://opencollective.com/stdlib">financially supporting stdlib</a>. We greatly appreciate your continued support!</p>
</details>

# Buffer

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Buffer namespace.

<section class="installation">

## Installation

```bash
npm install @f1stnpm2/rerum-quod-porro
```

Alternatively,

-   To load the package in a website via a `script` tag without installation and bundlers, use the [ES Module][es-module] available on the [`esm`][esm-url] branch (see [README][esm-readme]).
-   If you are using Deno, visit the [`deno`][deno-url] branch (see [README][deno-readme] for usage intructions).
-   For use in Observable, or in browser/node environments, use the [Universal Module Definition (UMD)][umd] build available on the [`umd`][umd-url] branch (see [README][umd-readme]).

The [branches.md][branches-url] file summarizes the available branches and displays a diagram illustrating their relationships.

To view installation and usage instructions specific to each branch build, be sure to explicitly navigate to the respective README files on each branch, as linked to above.

</section>

<section class="usage">

## Usage

```javascript
var ns = require( '@f1stnpm2/rerum-quod-porro' );
```

#### ns

Buffer namespace.

```javascript
var o = ns;
// returns {...}
```

The namespace contains the following:

<!-- <toc pattern="*"> -->

<div class="namespace-toc">

-   <span class="signature">[`allocUnsafe( size )`][@f1stnpm2/rerum-quod-porro/alloc-unsafe]</span><span class="delimiter">: </span><span class="description">allocate a buffer having a specified number of bytes.</span>
-   <span class="signature">[`Buffer()`][@f1stnpm2/rerum-quod-porro/ctor]</span><span class="delimiter">: </span><span class="description">Buffer constructor.</span>
-   <span class="signature">[`arraybuffer2buffer( buf[, byteOffset[, length]] )`][@f1stnpm2/rerum-quod-porro/from-arraybuffer]</span><span class="delimiter">: </span><span class="description">allocate a buffer from an ArrayBuffer.</span>
-   <span class="signature">[`copyBuffer( buffer )`][@f1stnpm2/rerum-quod-porro/from-buffer]</span><span class="delimiter">: </span><span class="description">copy buffer data to a new `Buffer` instance.</span>
-   <span class="signature">[`string2buffer( str[, encoding] )`][@f1stnpm2/rerum-quod-porro/from-string]</span><span class="delimiter">: </span><span class="description">allocate a buffer containing a provided string.</span>
-   <span class="signature">[`reviveBuffer( key, value )`][@f1stnpm2/rerum-quod-porro/reviver]</span><span class="delimiter">: </span><span class="description">revive a JSON-serialized Buffer.</span>
-   <span class="signature">[`buffer2json( buffer )`][@f1stnpm2/rerum-quod-porro/to-json]</span><span class="delimiter">: </span><span class="description">return a JSON representation of a Buffer.</span>

</div>

<!-- </toc> -->

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- TODO: better examples -->

<!-- eslint no-undef: "error" -->

```javascript
var objectKeys = require( '@stdlib/utils/keys' );
var ns = require( '@f1stnpm2/rerum-quod-porro' );

console.log( objectKeys( ns ) );
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

Copyright &copy; 2016-2024. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@f1stnpm2/rerum-quod-porro.svg
[npm-url]: https://npmjs.org/package/@f1stnpm2/rerum-quod-porro

[test-image]: https://github.com/f1stnpm2/rerum-quod-porro/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/f1stnpm2/rerum-quod-porro/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/f1stnpm2/rerum-quod-porro/main.svg
[coverage-url]: https://codecov.io/github/f1stnpm2/rerum-quod-porro?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/f1stnpm2/rerum-quod-porro.svg
[dependencies-url]: https://david-dm.org/f1stnpm2/rerum-quod-porro/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/f1stnpm2/rerum-quod-porro/tree/deno
[deno-readme]: https://github.com/f1stnpm2/rerum-quod-porro/blob/deno/README.md
[umd-url]: https://github.com/f1stnpm2/rerum-quod-porro/tree/umd
[umd-readme]: https://github.com/f1stnpm2/rerum-quod-porro/blob/umd/README.md
[esm-url]: https://github.com/f1stnpm2/rerum-quod-porro/tree/esm
[esm-readme]: https://github.com/f1stnpm2/rerum-quod-porro/blob/esm/README.md
[branches-url]: https://github.com/f1stnpm2/rerum-quod-porro/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/f1stnpm2/rerum-quod-porro/main/LICENSE

<!-- <toc-links> -->

[@f1stnpm2/rerum-quod-porro/alloc-unsafe]: https://github.com/f1stnpm2/rerum-quod-porro/tree/main/alloc-unsafe

[@f1stnpm2/rerum-quod-porro/ctor]: https://github.com/f1stnpm2/rerum-quod-porro/tree/main/ctor

[@f1stnpm2/rerum-quod-porro/from-arraybuffer]: https://github.com/f1stnpm2/rerum-quod-porro/tree/main/from-arraybuffer

[@f1stnpm2/rerum-quod-porro/from-buffer]: https://github.com/f1stnpm2/rerum-quod-porro/tree/main/from-buffer

[@f1stnpm2/rerum-quod-porro/from-string]: https://github.com/f1stnpm2/rerum-quod-porro/tree/main/from-string

[@f1stnpm2/rerum-quod-porro/reviver]: https://github.com/f1stnpm2/rerum-quod-porro/tree/main/reviver

[@f1stnpm2/rerum-quod-porro/to-json]: https://github.com/f1stnpm2/rerum-quod-porro/tree/main/to-json

<!-- </toc-links> -->

</section>

<!-- /.links -->
