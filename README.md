# babel-preset-es2015-generators-async

> babel-preset-es2015 minus regenerator plus async-to-module-method.

## Install

```sh
$ npm install --save-dev babel-preset-es2015-generators-async
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["es2015-generators-async"]
}
```

### Via CLI

```sh
$ babel script.js --presets es2015-generators-async
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  presets: ["es2015-generators-async"]
});
```
