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

# Platform

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] [![dependencies][dependencies-image]][dependencies-url]

> Platform on which the current process is running.

<section class="installation">

## Installation

```bash
npm install @stdlib/os-platform
```

</section>

<section class="usage">

## Usage

```javascript
var PLATFORM = require( '@stdlib/os-platform' );
```

#### PLATFORM

[Platform][process-platform] on which the current process is running.

```javascript
console.log( PLATFORM );
// => <string>
```

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- eslint no-undef: "error" -->

```javascript
var PLATFORM = require( '@stdlib/os-platform' );

if ( PLATFORM === 'win32' ) {
    console.log( 'Running on a PC...' );
} else if ( PLATFORM === 'darwin' ) {
    console.log( 'Running on a Mac...' );
} else {
    console.log( 'Running on something else...' );
}
```

</section>

<!-- /.examples -->

* * *

<section class="cli">

## CLI

<section class="installation">

## Installation

To use the module as a general utility, install the module globally

```bash
npm install -g @stdlib/os-platform
```

</section>

<section class="usage">

### Usage

```text
Usage: platform [options]

Options:

  -h,    --help                Print this message.
  -V,    --version             Print the package version.
```

</section>

<!-- /.usage -->

<section class="examples">

### Examples

```bash
$ platform
```

</section>

<!-- /.examples -->

</section>

<!-- /.cli -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2021. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/os-platform.svg
[npm-url]: https://npmjs.org/package/@stdlib/os-platform

[test-image]: https://github.com/stdlib-js/os-platform/actions/workflows/test.yml/badge.svg
[test-url]: https://github.com/stdlib-js/os-platform/actions/workflows/test.yml

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/os-platform/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/os-platform?branch=main

[dependencies-image]: https://img.shields.io/david/stdlib-js/os-platform
[dependencies-url]: https://david-dm.org/stdlib-js/os-platform/main

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/os-platform/main/LICENSE

[process-platform]: https://nodejs.org/api/process.html#process_process_platform

</section>

<!-- /.links -->
