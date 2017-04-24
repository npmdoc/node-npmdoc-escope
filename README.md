# npmdoc-escope

#### api documentation for  [escope (v3.6.0)](http://github.com/estools/escope)  [![npm package](https://img.shields.io/npm/v/npmdoc-escope.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-escope) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-escope.svg)](https://travis-ci.org/npmdoc/node-npmdoc-escope)

#### ECMAScript scope analyzer

[![NPM](https://nodei.co/npm/escope.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/escope)

- [https://npmdoc.github.io/node-npmdoc-escope/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-escope/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-escope/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-escope/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-escope/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-escope/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/estools/escope/issues"
    },
    "dependencies": {
        "es6-map": "^0.1.3",
        "es6-weak-map": "^2.0.1",
        "esrecurse": "^4.1.0",
        "estraverse": "^4.1.1"
    },
    "description": "ECMAScript scope analyzer",
    "devDependencies": {
        "babel": "^6.3.26",
        "babel-preset-es2015": "^6.3.13",
        "babel-register": "^6.3.13",
        "browserify": "^13.0.0",
        "chai": "^3.4.1",
        "espree": "^3.1.1",
        "esprima": "^2.7.1",
        "gulp": "^3.9.0",
        "gulp-babel": "^6.1.1",
        "gulp-bump": "^1.0.0",
        "gulp-eslint": "^1.1.1",
        "gulp-espower": "^1.0.2",
        "gulp-filter": "^3.0.1",
        "gulp-git": "^1.6.1",
        "gulp-mocha": "^2.2.0",
        "gulp-plumber": "^1.0.1",
        "gulp-sourcemaps": "^1.6.0",
        "gulp-tag-version": "^1.3.0",
        "jsdoc": "^3.4.0",
        "lazypipe": "^1.0.1",
        "vinyl-source-stream": "^1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "e01975e812781a163a6dadfdd80398dc64c889c3",
        "tarball": "https://registry.npmjs.org/escope/-/escope-3.6.0.tgz"
    },
    "engines": {
        "node": ">=0.4.0"
    },
    "gitHead": "aa35861faa76a09f01203dee3497a939d70b463c",
    "homepage": "http://github.com/estools/escope",
    "license": "BSD-2-Clause",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "constellation"
        },
        {
            "name": "michaelficarra"
        },
        {
            "name": "nzakas"
        }
    ],
    "name": "escope",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/estools/escope.git"
    },
    "scripts": {
        "jsdoc": "jsdoc src/*.js README.md",
        "lint": "gulp lint",
        "test": "gulp travis",
        "unit-test": "gulp test"
    },
    "version": "3.6.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
