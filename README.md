# npmtest-elasticdump

#### basic test coverage for  elasticdump (v3.1.0)  [![npm package](https://img.shields.io/npm/v/npmtest-elasticdump.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-elasticdump) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-elasticdump.svg)](https://travis-ci.org/npmtest/node-npmtest-elasticdump)

#### import and export tools for elasticsearch

[![NPM](https://nodei.co/npm/elasticdump.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/elasticdump)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-elasticdump/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-elasticdump/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-elasticdump/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-elasticdump/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-elasticdump/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-elasticdump/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-elasticdump/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-elasticdump/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-elasticdump/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-elasticdump/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-elasticdump/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-elasticdump/build/test-report.html](https://npmtest.github.io/node-npmtest-elasticdump/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-elasticdump/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-elasticdump/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-elasticdump/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-elasticdump/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-elasticdump/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-elasticdump/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-elasticdump/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-elasticdump/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "Evan Tahler <evantahler@gmail.com>",
    "name": "elasticdump",
    "description": "import and export tools for elasticsearch",
    "version": "3.1.0",
    "license": "Apache-2.0",
    "repository": {
        "type": "git",
        "url": "git://github.com/taskrabbit/elasticsearch-dump.git"
    },
    "main": "elasticdump.js",
    "keywords": [
        "elasticsearch",
        "dump",
        "elasticdump",
        "import",
        "export",
        "transfer",
        "migrate",
        "migartion",
        "elasitic",
        "cluster",
        "elastic-dump",
        "elastic dump"
    ],
    "engines": {
        "node": ">=4.0.0"
    },
    "dependencies": {
        "JSONStream": "^1.2.0",
        "async": "^2.0.1",
        "aws4": "^1.4.1",
        "awscred": "^1.2.0",
        "ini": "^1.3.4",
        "optimist": "latest",
        "request": "2.x.x"
    },
    "devDependencies": {
        "mocha": "latest",
        "should": "latest",
        "standard": "^8.6.0"
    },
    "standard": {
        "globals": [
            "describe",
            "it",
            "describe",
            "before",
            "beforeEach",
            "after",
            "afterEach"
        ]
    },
    "bin": {
        "elasticdump": "./bin/elasticdump",
        "multielasticdump": "./bin/multielasticdump"
    },
    "scripts": {
        "test": "standard && mocha"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
