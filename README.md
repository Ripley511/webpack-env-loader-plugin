# webpack2-env-loader-plugin

A plugin that extends `DefinePlugin` to help load configuration based on environment.

This plugin is a simple adaptation of k88hudson webpack-env-loader-plugin for Webpack, but uses Webpack 2.1 (no annoying error message).

Check out [k88hudson repository](https://github.com/k88hudson/webpack-env-loader-plugin) for configuration instructions.

## Installation

First, install with npm:

```
npm install webpack2-env-loader-plugin --save-dev
```

Add an instance of the plugin to `webpack.config.js`:

```js
const EnvLoaderWebpack2Plugin = require("webpack2-env-loader-plugin");

module.exports = {
  ...
  plugins: [
    new EnvLoaderWebpack2Plugin(options)
  ]
};
```
