# npmtest-stream-http

#### basic test coverage for  [stream-http (v2.7.0)](https://github.com/jhiesey/stream-http#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-stream-http.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-stream-http) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-stream-http.svg)](https://travis-ci.org/npmtest/node-npmtest-stream-http)

#### Streaming http in the browser

[![NPM](https://nodei.co/npm/stream-http.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/stream-http)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-stream-http/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-stream-http/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-stream-http/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-stream-http/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-stream-http/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-stream-http/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-stream-http/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-stream-http/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-stream-http/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-stream-http/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-stream-http/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-stream-http/build/test-report.html](https://npmtest.github.io/node-npmtest-stream-http/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-stream-http/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-stream-http/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-stream-http/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-stream-http/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-stream-http/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-stream-http/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-stream-http/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-stream-http/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "stream-http",
    "version": "2.7.0",
    "description": "Streaming http in the browser",
    "main": "index.js",
    "repository": {
        "type": "git",
        "url": "git://github.com/jhiesey/stream-http.git"
    },
    "scripts": {
        "test": "npm run test-node && ([ -n \"${TRAVIS_PULL_REQUEST}\" -a \"${TRAVIS_PULL_REQUEST}\" != 'false' ] || npm run test-browser)",
        "test-node": "tape test/node/*.js",
        "test-browser": "zuul --no-coverage -- test/browser/*.js",
        "test-browser-local": "zuul --local 8080 --no-coverage -- test/browser/*.js"
    },
    "author": "John Hiesey",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/jhiesey/stream-http/issues"
    },
    "homepage": "https://github.com/jhiesey/stream-http#readme",
    "keywords": [
        "http",
        "stream",
        "streaming",
        "xhr",
        "http-browserify"
    ],
    "dependencies": {
        "builtin-status-codes": "^3.0.0",
        "inherits": "^2.0.1",
        "readable-stream": "^2.2.6",
        "to-arraybuffer": "^1.0.0",
        "xtend": "^4.0.0"
    },
    "devDependencies": {
        "basic-auth": "^1.0.3",
        "brfs": "^1.4.0",
        "cookie-parser": "^1.3.5",
        "express": "^4.15.2",
        "tape": "^4.0.0",
        "ua-parser-js": "^0.7.7",
        "webworkify": "^1.0.2",
        "zuul": "^3.10.3"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
