# docdash

A simple JSDoc to Markdown documentation generator.

## Install

yarn
```bash {.copy-clip}
yarn add @flavs/docdash
```

npm
```bash {.copy-clip}
npm i @flavs/docdash
```

## Usage

```js
var docdash = require('@flavs/docdash');

var markdown = docdash({
  'path': filepath,
  'url': 'https://github.com/username/project/blob/master/my.js'
});
```
