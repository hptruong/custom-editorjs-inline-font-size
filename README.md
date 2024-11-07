![](https://badgen.net/badge/Editor.js/v2.0/blue)

# Font Size tool
Font size inline tool for the [Editor.js](https://editorjs.io).

## Installation

### Install via NPM or Yarn

Get the package

```shell
npm i --save-dev custom-editorjs-inline-font-size-tool
```
or
```shell
yarn add custom-editorjs-inline-font-size-tool --dev
```

Include module in your application

```javascript
const FontSizeTool = require('custom-editorjs-inline-font-size-tool');
```

### Upload to your project's source dir
1. Download folder `dist` from repository
2. Add `dist/bundle.js` file to your page.

## Usage
Add a new Tool to the `tools` property of the Editor.js initial config.

```javascript
var editor = EditorJS({
  ...
  
  tools: {
    ...
    fontSize: {
      class: FontSizeTool,
      config: {
        fontSizeList: [
          { label: '10', value: '1' },
          { label: '12', value: '2' },
          { label: '16', value: '3' },
          { label: '18', value: '4' },
          { label: '24', value: '5' },
          { label: '32', value: '6' },
          { label: '48', value: '7' }
        ]
      }
    }
  }
  ...
});
```




