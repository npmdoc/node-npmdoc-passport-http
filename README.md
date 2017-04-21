# npmdoc-passport-http

#### api documentation for  passport-http (v0.3.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-passport-http.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-passport-http) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-passport-http.svg)](https://travis-ci.org/npmdoc/node-npmdoc-passport-http)

#### HTTP Basic and Digest authentication strategies for Passport.

[![NPM](https://nodei.co/npm/passport-http.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/passport-http)

- [https://npmdoc.github.io/node-npmdoc-passport-http/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-passport-http/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-passport-http/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-passport-http/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-passport-http/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-passport-http/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "passport-http",
    "version": "0.3.0",
    "description": "HTTP Basic and Digest authentication strategies for Passport.",
    "keywords": [
        "passport",
        "http",
        "basic",
        "digest",
        "auth",
        "authn",
        "authentication"
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/jaredhanson/passport-http.git"
    },
    "bugs": {
        "url": "http://github.com/jaredhanson/passport-http/issues"
    },
    "author": {
        "name": "Jared Hanson",
        "url": "http://www.jaredhanson.net/"
    },
    "licenses": [
        {
            "type": "MIT",
            "url": "http://www.opensource.org/licenses/MIT"
        }
    ],
    "main": "./lib/passport-http",
    "dependencies": {
        "passport-strategy": "1.x.x"
    },
    "devDependencies": {
        "vows": "0.8.x"
    },
    "scripts": {
        "test": "NODE_PATH=lib node_modules/.bin/vows test/*-test.js test/**/*-test.js"
    },
    "engines": {
        "node": ">= 0.4.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
