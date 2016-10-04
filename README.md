# Vanilla ES6 (ES2015)


## Installation

To get started with this example, navigate into the example folder and install the NPM modules.
```bash
cd todomvc/examples/vanilla-es6
npm install
```

## Compiling ES6 to ES5

After NPM modules have been installed, use the pre-defined Babel script to convert the `src` files. Browserify is also used so that `module.exports` and `require()` can be run in your browser.

```bash
npm run compile
```

## Implementation

Uses [Google Closure Compiler](https://developers.google.com/closure/compiler/) to compile ES6 code to ES5, which is then readable by all browsers.
