JavaScript Development Environment
==================================

## Chosen Tools/Features:
**Editor** - VSCode (with .editorconfig)
**Package Manager** - npm
**Development Server** - Express
**Automation** - npm scripts
**Transpiler** - Babel
**Bundler** - Webpack
**Linter** - ESLint
**Testing** - Mocha (framework), Chai (assertion library), JSDOM (helper library)
**Continuous Integration** - Travis CI, Appveyor
**HTTP Calls** - Fetch (with polyfill)
**Minification** - Bundler (Webpack)
**Dynamic HTML Generation** - HTML-webpack-plugin
**Bundle Splitting** - Bundler (Webpack)
**Cache Busting** - Bundler (Webpack)
**Error Logging** - Track:js recommended (not included, price gate)


## Desired Improvements:
-Generate CSS Sourcemaps
-Linting occasionally outputs twice in console

## JS Project Structure Tips:
**1)** JS belongs in a .js file
**2)** Consider organizing by feature (larger projects) vs. file type (MVC)
**3)** Extract logic to POJOs (your JS logic should exist outside of framework components)