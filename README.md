[![npm](https://img.shields.io/npm/v/@kronos-integration/test-interceptor.svg)](https://www.npmjs.com/package/@kronos-integration/test-interceptor)
[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)
[![minified size](https://badgen.net/bundlephobia/min/@kronos-integration/test-interceptor)](https://bundlephobia.com/result?p=@kronos-integration/test-interceptor)
[![downloads](http://img.shields.io/npm/dm/@kronos-integration/test-interceptor.svg?style=flat-square)](https://npmjs.org/package/@kronos-integration/test-interceptor)
[![Build Status](https://travis-ci.com/Kronos-Integration/test-interceptor.svg?branch=master)](https://travis-ci.com/Kronos-Integration/test-interceptor)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/Kronos-Integration/test-interceptor.git)
[![styled with prettier](https://img.shields.io/badge/styled_with-prettier-ff69b4.svg)](https://github.com/prettier/prettier)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)
[![Known Vulnerabilities](https://snyk.io/test/github/Kronos-Integration/test-interceptor/badge.svg)](https://snyk.io/test/github/Kronos-Integration/test-interceptor)
[![codecov.io](http://codecov.io/github/Kronos-Integration/test-interceptor/coverage.svg?branch=master)](http://codecov.io/github/Kronos-Integration/test-interceptor?branch=master)
[![Coverage Status](https://coveralls.io/repos/Kronos-Integration/test-interceptor/badge.svg)](https://coveralls.io/r/Kronos-Integration/test-interceptor)

# @kronos-integration/test-interceptor

test support for kronos interceptors

# API

<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

### Table of Contents

-   [interceptorTest](#interceptortest)
    -   [Parameters](#parameters)

## interceptorTest

### Parameters

-   `t` **ava** ava test runner
-   `factory` **Class** interceptor Class
-   `config` **[Object](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Object)** to assing
-   `expected` **any**  (optional, default `{}`)
-   `endpoint` **Endpoint** endpoint to assign
-   `args` **[Array](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Array)**  (optional, default `[]`)
-   `next` **[Function](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Statements/function)**  (optional, default `(...args)=>0`)
-   `asserts`   (optional, default `()=>{}`)

# install

With [npm](http://npmjs.org) do:

```shell
npm install @kronos-integration/test-interceptor
```

# license

BSD-2-Clause
