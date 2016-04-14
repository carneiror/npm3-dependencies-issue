# npm3-dependencies-issue
Small example to expose the current NPM3 flat dependencies issues

To run:

```
$ npm install
$ npm ls browserify karma-browserify
$ node
> require.resolve('browserify')
'.../example-module/node_modules/browserify/index.js'
```
