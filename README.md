# electron-react-typescript-playground

Easy Playground for TypeScript + React on Electron.

**DON'T USE FOR PRODUCTION**

## Usage

Write React application inside `src` dir.

If you want to write js, edit `tsconfig.json` as `"allowJs": true`.

## How it works

`ts-node` enables typescript compiling at runtime.

```javascript
// preload.js
require('ts-node').register();
```