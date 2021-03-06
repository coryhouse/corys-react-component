# Cory's React Component

[![Travis][build-badge]][build]
[![npm package][npm-badge]][npm]
[![Coveralls][coveralls-badge]][coveralls]

Cory's React component is the premeire Hello World component on Summit's org.

## Install

```
npm i @summitllc/corys-react-component
```

## Props

| Name    | Default      | Required | Description             |
| ------- | ------------ | -------- | ----------------------- |
| message | Hello world! | Yes      | The thing ya wanna say. |

## Usage Example

```js
import React from "react";
import CorysReactComponent from "@summitllc/corys-react-component";

function Demo() {
  return <CorysReactComponent message={"Your message here"} />;
}

export default Demo;
```

[build-badge]: https://img.shields.io/travis/user/repo/master.png?style=flat-square
[build]: https://travis-ci.org/user/repo
[npm-badge]: https://img.shields.io/npm/v/npm-package.png?style=flat-square
[npm]: https://www.npmjs.org/package/npm-package
[coveralls-badge]: https://img.shields.io/coveralls/user/repo/master.png?style=flat-square
[coveralls]: https://coveralls.io/github/user/repo
