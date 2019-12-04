# react-app-rewire-source-map-loader

Add [source-map-loader](https://github.com/webpack-contrib/source-map-loader) to a [react-app-rewired](https://github.com/timarney/react-app-rewired) config.

```js
/* config-overrides.js */

const rewireSourceMap = require('react-app-rewire-source-map-loader')

module.exports = function override(config, env) {
    // ...
    config = rewireSourceMap(config, env)
    // ...
    return config
}
```
