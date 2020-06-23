# @acastemoreno/first-package

This is my first package (proof of concept) and greets.

## Installation

With `yarn`

```bash
yarn add @acastemoreno/first-package
```

With npm

```bash
npm install @acastemoreno/first-package
```

## Usage

Import the module in your file `js`

```js
import hello from "@acastemoreno/first-package"; //ESM

const hello = require("@acastemoreno/first-package"); //CommonJS
```

You will have available the function `hello`.

```js
hello("amiguito");
("Hello amiguito");
```
