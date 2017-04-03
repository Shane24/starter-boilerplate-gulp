# starter-boilerplate-gulp
A gulp project boilerplate.

## Features

* enable [ES2015 features](https://babeljs.io/docs/learn-es2015/) using [Babel](https://babeljs.io)
* CSS Autoprefixing
* Built-in preview server with BrowserSync
* Compile Sass with [libsass](http://libsass.org)
* Lint your scripts
* Map compiled CSS to source stylesheets with source maps
* Image optimization
* Wire-up dependencies installed with [Bower](http://bower.io)


## Uses libsass

Libsass is feature-wise not fully compatible with Ruby Sass. Check out [this](http://sass-compatibility.github.io) curated list of incompatibilities to find out which features are missing. Libsass is however much faster.


## Getting Started

- Run `gulp serve` to preview and watch for changes
- Run `bower install --save <package>` to install frontend dependencies
- Run `gulp serve:test` to run the tests in the browser
- Run `gulp` to build your webapp for production into [dist] folder
- Run `gulp serve:dist` to preview the production build


## Notes
- One of the dependencies (Wiredep) doesn't like blank files and can trigger an error; if you're getting unknown errors, first check to make sure none of your files are blank/empty.
- Don't need something, such as tests or linting? Just remove the task in the gulpfile.