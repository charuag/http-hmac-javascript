# HTTP HMAC Signer for JavaScript

HMAC Request Signer is a JavaScript library that implements the version 2.0 of the [HTTP HMAC Spec](https://github.com/acquia/http-hmac-spec/tree/2.0)
to sign RESTful Web API requests and verify responses.

## Development Prerequisites

Before further development, please ensure the following tools are installed on your computer.

* [Git](http://git-scm.com/)
* [Node.js](http://nodejs.org/) (with NPM)

You can use the following commands to check if you already have those tools:
```
git --version
node -v
npm -v
```

## Installation

* `git clone <repository-url>` this repository.
* Change into the new directory.
* `npm install`

## Files
* _demo/_ - Visit the _get.hmtl_ and _post.html_ to see the demo in action.
* _lib/_ - Transpiled/compiled result library file.
  * _es5/_ - Traspiled ES5 version, compiled with dependencies.
  * _es6/_ - ES6 version, compiled with dependencies.
* _src/_ - All the source files in ES6. Code changes should be made here.
  * _demo/_ - Demo files to show how the library can be used.
  * _hmac.js_ - The source file of the library.

## Build

* Make code changes in _src/_ directory.
* In root directory, run ```gulp build-demo```. Alternatively, you can run ```gulp``` to keep gulp on watch to automatically compile/transpile all file changes.
