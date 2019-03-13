# docdash

A simple JSDoc to Markdown documentation generator.

## Install

yarn
```bash {.copy-clip}
yarn add @flavioespinoza/docdash
```

npm
```bash {.copy-clip}
npm i @flavioespinoza/docdash
```

## Usage

```js
var docdash = require('docdash');

var markdown = docdash({
  'path': filepath,
  'url': 'https://github.com/username/project/blob/master/my.js'
});
```
