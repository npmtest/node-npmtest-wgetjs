# npmtest-wgetjs

#### basic test coverage for  [wgetjs (v0.3.6)](https://github.com/angleman/wgetjs#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-wgetjs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-wgetjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-wgetjs.svg)](https://travis-ci.org/npmtest/node-npmtest-wgetjs)

#### Ultra simple async retrieval of remote files over http or https

[![NPM](https://nodei.co/npm/wgetjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/wgetjs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-wgetjs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-wgetjs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-wgetjs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-wgetjs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-wgetjs/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-wgetjs/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-wgetjs/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-wgetjs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-wgetjs/tree/gh-pages/build)|

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
    "author": {
        "name": "angleman"
    },
    "bugs": {
        "url": "https://github.com/angleman/wgetjs/issues"
    },
    "dependencies": {
        "request": "~2.27.0"
    },
    "description": "Ultra simple async retrieval of remote files over http or https",
    "devDependencies": {
        "grunt": "~0.4.1",
        "grunt-bump": "~0.0.11",
        "grunt-license": "~0.1.4",
        "license-md": "~0.2.5",
        "mocha": "~1.12.0",
        "should": "~1.2.2"
    },
    "directories": {},
    "dist": {
        "shasum": "27173c9f8973cae2d347f280c63b400513402bf0",
        "tarball": "https://registry.npmjs.org/wgetjs/-/wgetjs-0.3.6.tgz"
    },
    "engines": {
        "node": ">=0.8.6"
    },
    "gitHead": "2270a48f4efa77572c48e197e08ee0d6dd259d0d",
    "homepage": "https://github.com/angleman/wgetjs#readme",
    "keywords": [
        "curl",
        "wget",
        "download",
        "file",
        "http",
        "https"
    ],
    "license": "MIT",
    "main": "wget.js",
    "maintainers": [
        {
            "name": "angleman"
        }
    ],
    "name": "wgetjs",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/angleman/wgetjs.git"
    },
    "scripts": {
        "TESTS.md": "mocha -R markdown test/*.js > TESTS.md",
        "test": "mocha -R list test/*.js"
    },
    "version": "0.3.6",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
