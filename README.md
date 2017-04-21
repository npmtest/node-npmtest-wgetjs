# npmtest-wgetjs

#### basic test coverage for  wgetjs (v0.3.6)  [![npm package](https://img.shields.io/npm/v/npmtest-wgetjs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-wgetjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-wgetjs.svg)](https://travis-ci.org/npmtest/node-npmtest-wgetjs)

#### Ultra simple async retrieval of remote files over http or https

[![NPM](https://nodei.co/npm/wgetjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/wgetjs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-wgetjs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-wgetjs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-wgetjs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-wgetjs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-wgetjs/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-wgetjs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-wgetjs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-wgetjs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-wgetjs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-wgetjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-wgetjs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-wgetjs/build/test-report.html](https://npmtest.github.io/node-npmtest-wgetjs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-wgetjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-wgetjs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-wgetjs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-wgetjs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-wgetjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-wgetjs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-wgetjs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-wgetjs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "wgetjs",
    "version": "0.3.6",
    "description": "Ultra simple async retrieval of remote files over http or https",
    "main": "wget.js",
    "scripts": {
        "test": "mocha -R list test/*.js",
        "TESTS.md": "mocha -R markdown test/*.js > TESTS.md"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/angleman/wgetjs.git"
    },
    "keywords": [
        "curl",
        "wget",
        "download",
        "file",
        "http",
        "https"
    ],
    "author": "angleman",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/angleman/wgetjs/issues"
    },
    "engines": {
        "node": ">=0.8.6"
    },
    "dependencies": {
        "request": "~2.27.0"
    },
    "devDependencies": {
        "license-md": "~0.2.5",
        "grunt": "~0.4.1",
        "grunt-bump": "~0.0.11",
        "grunt-license": "~0.1.4",
        "mocha": "~1.12.0",
        "should": "~1.2.2"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
